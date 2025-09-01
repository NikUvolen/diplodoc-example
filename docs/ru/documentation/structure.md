# Структура проекта

```
back_out
|-- apps                    # директория с приложениями Django
    |-- companies
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- contacts
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- crp
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- faculties
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- practices
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- specialities
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- themes
        |-- migrations/
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- userauth
        |-- __init__.py
        |-- apps.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
    |-- users
        |-- management
            |-- commands
                |-- __init__.py
                |-- create_companies.py
                |-- generate.py
                |-- get_companies.py
                |-- get_group_link.py
                |-- load_from_excel.py
        |-- __init__.py
        |-- apps.py
        |-- models.py
        |-- serializers.py
        |-- urls.py
        |-- views.py
|-- out                     # главная директория проекта
    |-- asgi.py
    |-- settings.py         # файл настроек
    |-- urls.py             # файл зависимостей
    |-- wsgi.py
|-- manage.py               # 
|-- req.txt                 # зависимости проекта
```
