### Документация для API Yatube : http://127.0.0.1:8000/redoc/


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/xxx
```

```
cd yatube_api
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```


### Создание суперпользователя

Для создания суперпользователя выполните команду:

```
(venv) $ python manage.py createsuperuser
```
Username (leave blank to use 'user'): # Придумайте логин (например, admin)
```
Email address: # укажите почту
```
Password: # придумайте пароль
```
Password (again): # повторите пароль
```
Superuser created successfully. 
```