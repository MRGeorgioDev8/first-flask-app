# Flaskio - первое учебное веб-приложение на Flask. Разработанное в рамках учебы в Top Academy

Flaskio - это простое веб-приложение, разработанное с использованием Flask, SQLite и Jinja2 для шаблонов.

## Структура проекта

Проект состоит из следующих файлов и директорий:

- `flaskio.py`: Основной файл приложения Flask, который содержит основной код приложения, включая маршруты и логику обработки запросов.
- `flskDB.py`: Модуль, содержащий класс `FlaskoDB`, который обеспечивает взаимодействие с базой данных SQLite.
- `db_fl.sql`: SQL-файл с определениями таблиц для базы данных.
- `static/`: Директория со статическими файлами, такими как изображения и таблицы стилей.
- `templates/`: Директория с шаблонами Jinja2 для отображения страниц.
- `requirements.txt`: Файл, содержащий список зависимостей Python, необходимых для запуска приложения.

## Установка зависимостей

Для установки зависимостей Python, указанных в файле `requirements.txt`, выполните следующую команду:

```
pip install -r requirements.txt
```


## Запуск приложения

- В терминале PyCharm клонируйте репозиторий проекта:

   ```bash
   git clone https://github.com/MRGeorgioDev8/first-flask-app.git

### Через командную строку (терминал):

Чтобы запустить приложение через командную строку (терминал), выполните следующую команду:

```
python flaskio.py
```


### Через PyCharm:

Откройте файл `flaskio.py` в PyCharm.
Нажмите кнопку "Run" (зеленый треугольник) на панели инструментов.
Перейдите по ссылке сервера Flask

## Описание функциональности

- Главная страница отображает список доступных статей и меню.
- Пользователи могут добавлять новые статьи через форму на странице добавления статьи.
- Каждая статья имеет свою собственную страницу с полным текстом.
- Пользователи могут удалять статьи.

## Зависимости

- Flask 3.0.3
- Jinja2 3.1.3
- SQLite (встроен в Python)
- Другие зависимости, указанные в файле requirements.txt

## Дополнительная информация

Этот проект представляет собой простое веб-приложение, разработанное в рамках учебы в Top Academy с использованием Flask и SQLite. Он демонстрирует базовые принципы веб-разработки на Python с использованием фреймворка Flask.
