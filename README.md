# API_FINAL_YATUBE

API_Final - законченная версия API для yatube. 


## 1) Склонировать репозиторий
## 2) Создать и активировать виртуальное окружение для проекта

python -m venv venv

. venv/Scripts/activate

## 3) Установить зависимости
python pip install -r requirements.txt

## 4) Сделать миграции
python manage.py makemigrations
python manage.py migrate

## 5) Запустить сервер
python manage.py runserver