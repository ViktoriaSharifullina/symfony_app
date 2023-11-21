# Веб-приложение на Symfony в стиле Twitter

![Symfony Logo](https://symfony.com/logos/symfony_black_02.png)

## Описание
Это веб-приложение, разработанное в рамках курса на платформе Udemy. Это приложение представляет собой упрощенный аналог Twitter, предоставляя функциональность авторизации, регистрации, создания постов, лайков, комментариев, а также добавления пользователей в избранное. Интерфейс приложения оформлен в светлой и темной темах с использованием Tailwind CSS.

## Основные функции

- **Авторизация и Регистрация:** Пользователи могут авторизоваться в существующем аккаунте или зарегистрироваться, чтобы создать новый аккаунт.

- **Создание Постов:** Пользователи могут писать посты, делиться своими мыслями и идеями с сообществом.

- **Лайки и Комментарии:** Посты поддерживают функцию лайков, а также возможность оставлять комментарии.

- **Избранное:** Пользователи могут добавлять других пользователей в избранное, следя за их активностью.

- **Интерфейс в Светлой и Темной Темах:** Приложение поддерживает два режима отображения - светлый и темный, обеспечивая удобство использования в любое время суток.

## Начало работы

1. Клонируйте репозиторий.
2. Установите зависимости с помощью `composer install`.
3. Скопируйте файл `.env.dist` в файл `.env` и настройте переменные окружения по необходимости.

### Запуск Docker контейнеров

Для локальной разработки используются Docker контейнеры. Запустите следующие команды для запуска контейнеров:

```bash
docker-compose up -d
```

Эта команда запустит два контейнера: MySQL (mariadb) и Adminer.

MySQL будет доступен по адресу 127.0.0.1:3306 с корневым паролем root.
Adminer, инструмент для управления базой данных, будет доступен по адресу 127.0.0.1:8080. Используйте следующие данные для подключения:
- Система: MySQL
- Сервер: mysql
- Имя пользователя: root
- Пароль: root
- База данных: оставьте пустым.

##  Запуск Symfony приложения

После запуска Docker контейнеров выполните следующие команды для запуска Symfony приложения:
