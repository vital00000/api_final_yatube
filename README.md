###  Прокет <<API для Yatube>>.

### Описание
```
API для Yatube предоставляет собой проект социальной сети в 
которой реализованы следующие возможности,
публиковать записи, комментировать записи, а так же подписываться 
или отписываться от авторов.
```

### Используемые технологии
```
Python 3.7, Django 2.2, DRF, JWT + Djoser
```

### Как запустить проект: 

Клонировать репозиторий и перейти в него в командной строке: 
```
git clone https://github.com/vitall00000/api_final_yatube.git
cd api_final_yatube
```
Cоздать и активировать виртуальное окружение: 
```
python -m venv env
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```

Выполнить миграции:
```
python manage.py migrate
```

Запустить проект: 
```
python manage.py runserver
https://github.com/vitall00000/api_final_yatube.git моя контактная страница
```