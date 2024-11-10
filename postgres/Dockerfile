# Используем официальный базовый образ PostgreSQL
FROM postgres:latest

# Устанавливаем переменные окружения для автоматического создания базы данных и пользователя
ENV POSTGRES_USER=vladimir_ulzutuev
ENV POSTGRES_PASSWORD=vladimir
ENV POSTGRES_DB=prod

# Копируем скрипт инициализации в образ
COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432