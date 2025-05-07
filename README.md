# API для проекта Yatube

Это API для социальной сети Yatube, разработанное с использованием Django REST Framework. API предоставляет возможность создавать посты, подписываться на авторов, комментировать записи и многое другое.

## Технологии

- Python 3.7+
- Django 3.2.16
- Django REST Framework 3.12.4

## Как запустить проект:

### 1. Клонируйте репозиторий:

```bash
git clone git@github.com:matvej-melikhov/api_final_yatube.git
```

### 2. Создайте и активируйте виртуальное окружение:

```bash
# Создание виртуального окружения
python3 -m venv venv

# Активация виртуального окружения
# Для Windows:
venv\Scripts\activate
# Для macOS/Linux:
source venv/bin/activate
```

### 3. Установите зависимости из файла requirements.txt:

```bash
pip install -r requirements.txt
```

### 4. Перейдите в директорию yatube_api и выполните миграции:

```bash
cd yatube_api
python manage.py migrate
```

### 5. Запустите проект:

```bash
python manage.py runserver
```

После запуска сервер будет доступен по адресу: http://127.0.0.1:8000/

## Тестирование

Для запуска тестов используйте команду:
```bash
pytest
```

## Документация API

После запуска проекта, документация API будет доступна по адресу:
- http://127.0.0.1:8000/redoc/
- http://127.0.0.1:8000/swagger/