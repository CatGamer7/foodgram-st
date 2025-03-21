# О проекте

Фудграм - платформа для распространения и управления рецептами.

# Технологии

- Django Rest Framework
- Djoser
- Postgres
- Nginx

# Как запустить

1. Создать и заполнить /backend/foodgram/.env файл с данными подключения к бд. Пример необходимых полей представлен в файле [.env.example](/backend/foodgram/.env.example). Убедитесь, что данные совместимы с настройкой бд в [docker-compose.yml](/infra/docker-compose.yml).

2. Перейдите в директорию [/infra](/infra/) и запустите docker-compose проект. Сбор статики, миграции и наполнение бд тестовыми данными происходит автоматически. 
```
cd infra
docker compose up
```
