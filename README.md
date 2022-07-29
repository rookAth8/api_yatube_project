API для Yatube

Реализован REST API для основных моделей проекта социальной сети Yatube. 
Для аутентификации пользователей примненяются JWT-токены, реализованы пермишены, фильтрации, сортировки и поиск по запросам клиентов.

Установка

1. Клонируем репозиторий 
$ git clone ...

2. Устанавливаем виртуальное окружение
$ python -m venv venv

3. Активируем виртуальное окружение
$ source venv/bin/activate

4. Устанавливаем зависимости
$ pip install -r requirements.txt

5. Создаем и применяем миграции
$ python manage.py makemigrations и $ python manage.py migrate

6. Запускаем тестовый сервер
$ python manage.py runserver
