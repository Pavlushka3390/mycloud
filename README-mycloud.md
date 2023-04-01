# mycloud
Дипломный проект  


### Запуск локально
___
1. Установить зависимости
```
pip install -r requirements.txt
```
2. Изменить в файле настроек данные базы данных
```
# mycloud/settings.py

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'cloud',
        'HOST': '127.0.0.1',
        'PORT': '5432',
        'USER': '***',
        'PASSWORD': '******',
    }
}
```
3. Провести миграции
```
python manage.py migrate
```
4. Запустить базовый sql-файл
```

5. Создать администратора
```
python manage.py createsuperuser
```
6. Запустить локальный сервер
```
python manage.py runserver
```




