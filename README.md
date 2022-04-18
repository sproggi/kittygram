# Kittygram
Проект для изучения базовых принципов API

## Стек:
Python 3, Django 2.2, DRF, PyJWT

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/sproggi/kittygram.git
```

```
cd kittygram2plus
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
| Endpoints | Response |
| ------ | ------ |
| [/api/v1/posts/] | All posts. GET, POST. |
| [/api/v1/posts/1/] | First id post. GET, PUT, PATCH, DELETE. |
| [/api/v1/posts/1/comments/] | Comments for post. GET, POST. |
| [/api/v1/posts/1/comments/1/] | Comment, in first post. GET, PUT, PATCH, DELETE.|
| [/api/v1/groups/] | Groups list. GET |
| [/api/v1/groups/1/] | First group. GET |
| [/api/v1/follow/] | Follow list, for request user. GET, POST. |
| [/api/v1/follow/1/] | First follow. GET, PUT, PATCH, DELETE. |
| [/api/v1/users/] | Users list. GET, CREATE |
| [/api/v1/jwt/create/] | JWT Token create. POST, |


[/api/v1/posts/]: <https://127.0.0.1/api/v1/posts/>
[/api/v1/posts/1/]: <https://127.0.0.1/api/v1/posts/1/>
[/api/v1/posts/1/comments/]: <https://127.0.0.1/api/v1/posts/1/comments/>
[/api/v1/posts/1/comments/1/]: <https://127.0.0.1/api/v1/posts/1/comments/1/>
[/api/v1/groups/]: <https://127.0.0.1/api/v1/groups/>
[/api/v1/groups/1/]: <https://127.0.0.1/api/v1/groups/1/>
[/api/v1/follow/]: <https://127.0.0.1/api/v1/follow/>
[/api/v1/follow/1/]: <https://127.0.0.1/api/v1/follow/1/>
[/api/v1/users/]: <https://127.0.0.1/api/v1/users/>
[/api/v1/jwt/create/]: <https://127.0.0.1/api/v1/jwt/create/>
