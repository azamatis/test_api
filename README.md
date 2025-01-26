# test_api
API взаимодействие с моделью



Запустим сервис titanic-service:
```
docker build -t titanic-service:latest .   

docker run --name titanic-service -p 300:5000 titanic-service:latest
```