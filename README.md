# Описание

Проект Kittygram – форум для публикации котов, где можно выбрать их цвет, год рождения, загрузить фото и присвоить им какие-либо достижения.

Ccылка на сайт – https://naprimerrrkittygram.ddns.net/

## Технологии

1. Python 3.10.6
2. Django==3.2.3
3. djangorestframework==3.12.4
4. djoser==2.1.0
5. gunicorn 20.1.0

## Как локально развернуть проект

1. Во время работы Docker'а перейти в директорию, где расположен файл requirements.txt
2. Создать и активировать виртуальное окружение
2. Ввести команду ```pip install -r requirements.txt```
3. В директории с файлом manage.py активировать миграции c помощью ```python manage.py makemigrations``` и ```python manage.py migrate```
4. Запустить бэкэнд командой ```python manage.py runserver```
5. Параллельно д запуска фронтенда нужно из любой директории ввести следующую команду ```curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs```
6. Далее перейдите в директорию /frontend/ и выполните команду ```npm i```
7. Запустите фронтенд командой ```npm run start```
8. Откройте браузер по ссылке http://127.0.0.1:3000/

## Шаблон наполнения env-файла

```
SECRET_KEY=...
```

## Автор

[Олег Призов](https://github.com/OlegPrizov)
