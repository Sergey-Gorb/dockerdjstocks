# Запуск c Nginx

docker run -d -v -p 5000:80 nginx:1.20.2 localhost:80 nginx

# Запуск с ginicorn

CMD ginicorn my_proj.wsgi -b 0.0.0.0:8000