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

## Запуск
1. Установка Django
```
pip install django
```

2. Создание проекта
```
django-admin startproject blog_project .
```
3. Создание приложения
```
python manage.py startapp blog
```
4. Создание миграций
```
python manage.py migrate
```
5. Запуск приложения
```
python manage.py runserver
```
   
## Результат
Starting development server at http://127.0.0.1:8000/
<img width="634" height="637" alt="image" src="https://github.com/user-attachments/assets/e49f5832-cd4b-4c05-ab40-8d9db41b62ef" />

http://127.0.0.1:8000/post/1/
<img width="526" height="445" alt="image" src="https://github.com/user-attachments/assets/7376d379-7c98-4f4a-973b-96156f98c278" />

http://127.0.0.1:8000/post/2/
<img width="547" height="485" alt="image" src="https://github.com/user-attachments/assets/89cdcf23-a074-4bb5-8f45-230a4d401feb" />

http://127.0.0.1:8000/admin/blog/post/
<img width="1920" height="718" alt="image" src="https://github.com/user-attachments/assets/d44db547-092a-4422-b90a-c7292749622e" />


