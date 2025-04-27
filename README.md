# CaloryTrackerWebsite

CaloryTrackerWebsite — сайт для учёта питания, тренировок и антропометрии, разработанный в рамках курсовой работы по дисциплине "Алгоритмизация и Программирование" (2 семестр).

## Технологии

- **Django** — веб-фреймворк
- **Django Auth** — система аутентификации пользователей
- **PostgreSQL** — база данных через Django ORM
- **Requests** — отправка HTTP-запросов к внешним API для получения данных о продуктах

## Быстрый старт

1. Клонировать репозиторий:

    ```bash
    git clone https://github.com/your-username/calorytrackerwebsite.git
    cd calorytrackerwebsite
    ```

2. Установить зависимости:

    ```bash
    pip install -r requirements.txt
    ```

3. Настроить переменные окружения:

    Создайте `.env` файл на основе `.env.example` и укажите параметры подключения к базе данных и внешним сервисам.

4. Применить миграции и запустить сервер:

    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

## Структура проекта

- `calorytracker/` — основное приложение проекта
- `users/` — управление регистрацией и авторизацией пользователей
- `nutrition/` — учёт питания
- `workouts/` — учёт тренировок
- `measurements/` — учёт антропометрических данных

## Требования

- Python 3.10+
- PostgreSQL
- Django 4.x

## Лицензия

Этот проект лицензирован под MIT License.
