# Запуск сервисов
Для запуска сервисов необходимо склонировать репозиторий
```shell
git clone https://github.com/aserialbug/HighLoadProject.git'
```
зайти в папку с проектом
```shell
cd HighLoadProject
```
и выполнить команду
```shell
docker compose up
```
После сборки API сервис бует запущен локально на порту 8080. Для вызова методов можно использовать приложенную коллекцию для Postman (UserService.postman_collection.json) или [Swagger](http://localhost:8080/swagger) севриса напрямую.