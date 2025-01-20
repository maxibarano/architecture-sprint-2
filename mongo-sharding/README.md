# pymongo-api

## Как запустить

Запускаем mongodb и приложение

```shell
docker compose up -d
```

Инициализируем шардирование и заполняем mongodb данными

```shell
./scripts/mongo-init.sh
```

## Как проверить

### Если вы запускаете проект на локальной машине

Откройте в браузере http://localhost:8080

## Task2
Общее количество документов и разбивка по шардам находится в ответе с http://localhost:8080 под ключом collections

https://drive.google.com/file/d/1DGUW6k4d9Q0gcsxZFaXa8RqgfoJ28DNR/view?usp=sharing