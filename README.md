# My Project: Docker Setup for Nginx and PostgreSQL

## Описание

Этот проект содержит два Docker-файла для запуска контейнеров с **nginx** и **PostgreSQL**. 
В контейнере nginx настроен запрет на POST-запросы, а в контейнере PostgreSQL автоматически создаются пользователь `vladimir_ulzutuev` и пустая база данных с тем же именем.

## Структура проекта

my_project/ 
├── nginx/ 
│ ├── Dockerfile # Docker-файл для сборки nginx 
│ └── nginx.conf # Конфигурация nginx с запретом на POST-запросы 
└── postgres/ 
│ ├── Dockerfile # Docker-файл для сборки PostgreSQL 
│ └── init.sql # Скрипт инициализации базы данных

