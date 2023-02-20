* Сборка образа:

```docker build -t my_nginx . ```

* Запуск контейнера:

```docker run --name=my_nginx_server -d -p 7070:80 my_nginx```

* Проверка работы контейнера:

```curl localhost:7070```