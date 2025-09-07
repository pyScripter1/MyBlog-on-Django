# MyBlog-on-Django
Создание блога на Django для начинающих.

Данный репозиторий поможет вам создать очень простой блог для выставления статей. Данное Django приложение содержит основное приложение blog и приложение настроек blog_project.

## Структура
```
MyBlog-on-Django/
│
├── blog/                           # Основное приложение
│   ├── migrations/
│   │   └── __init__.py
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── blog_project/                   # Папка с настройками проекта
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── static/                         # Статические файлы
│   └── css/
│       └── base.css
│
├── templates/                      # HTML-шаблоны
│   ├── base.html
│   ├── home.html
│   └── post_detail.html
│
├── .venv/                          # Виртуальное окружение
├── db.sqlite3                      # База данных
├── manage.py                       # Утилита управления Django
└── main.py                         # Главный исполняемый файл
```
