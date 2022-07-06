## REST API для проекта [Yatube](https://github.com/airatbakiev/yatube)

### Стек

- Python 3.7.0
- Django 2.2.16
- DRF 3.12.4

### Описание

Это практическое задание, выполненное при освоении Django Rest Framework


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/airatbakiev/api_final_yatube.git
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```
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
```

Откройте ***документацию*** API (с эндпоинтами и запросами), для этого перейдите на страницу:

```
http://localhost/redoc/
```
