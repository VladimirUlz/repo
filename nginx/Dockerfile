# Используем базовый образ Alpine для легковесности
FROM nginx:alpine

# Копируем наш конфигурационный файл в контейнер
COPY nginx.conf /etc/nginx/nginx.conf

# Открываем 80 порт для доступа
EXPOSE 80

# Запускаем nginx
CMD ["nginx", "-g", "daemon off;"]