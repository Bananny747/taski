# Taski
Приложение для планирования своих задач с любого устройства.

### Описание

Frontend: SPA на React
Backend: приложение на Django


### Технологии
#### Frontend
axios 1.2.1
bootstrap 5.2.3
react-dom 18.2.0
react-scripts 5.0.1
react 18.2.0
reactstrap 9.1.5
web-vitals 2.1.4

#### Backend
Django 3.2.3
djangorestframework 3.12.4
django-cors-headers 3.13.0


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Bananny747/taski.git
```

#### Backend
```
cd backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
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

Настроить settings.py:

```
CORS_ORIGIN_ALLOW_ALL = True
CORS_URLS_REGEX = r'^/api/.*$'

```

#### Frontend
```
cd frontend
```

Установить Node.js (внутри пакетный менеджер js - npm):

```
https://nodejs.org/en/download
```

Установить зависимости:

```
npm i
```

Запкстить:

```
npm run start
```
