# Kittygram
Проект для изучения базовых принципов API.
API для ведения базы котиков и их достижений.

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
### Аутентификация
| Endpoints | appointment | method |
| ------ | ------ | ------ |
| [/auth/users/] | Send pair username / password to sign up | POST |
| [/auth/jwt/create/] | Create JWT Token | POST |
| [/auth/jwt/refresh/] | Refresh JWT Token | POST |

### POST and GET requests
| Endpoints | appointment | method |
| ------ | ------ | ------ |
| [/cats/] | Get all posted cats | GET |
| [/cats/] | Post cats | POST |
| [/achievements/] | Get all achievements by cats | GET |
| [/achievements/] | Post achievements per cat | POST |


[/auth/users/]: <https://127.0.0.1:8000/auth/users/>
[/auth/jwt/create/]: <https://127.0.0.1:8000/auth/jwt/create/>
[/auth/jwt/refresh/]: <https://127.0.0.1:8000/auth/jwt/refresh/>
[/cats/]: <https://127.0.0.1:8000/cats/>
[/achievements/]: <https://127.0.0.1:8000/achievements/>

