# kittygram_final
### Описание проекта:

Kittygram предназначен для поднятия настроения путем выкладывания фото котиков и их достижений.

### Как запустить проект локально:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/lada-nk/kittygram_final.git
```

```
cd kittygram_final
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у вас windows

    ```
    source venv/scripts/activate
    ```

```
cd backend
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

### Примеры:

Получаем список всех котов или создаём нового кота:

```
api/cats/ (GET, POST)
```

Получаем, редактируем или удаляем кота по id:

```
api/cats/{cat_id}/ (GET, PUT, PATCH, DELETE)
```


### Использованные технологии:

Django REST framework:

```
https://www.django-rest-framework.org/
```

Pillow:

```
https://pillow.readthedocs.io/en/stable/
```

PyJWT:

```
https://pyjwt.readthedocs.io/en/stable/
```

Requests:

```
https://requests.readthedocs.io/en/latest/
```

### Workflow status:

![Kittigram workflow status]
(https://github.com/lada-nk/kittygram_final/actions/workflows/main.yml/badge.svg)
