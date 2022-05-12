# api_final

api final

Описание

API_FINAL_YATUBE проект по созданию API для блог платформы yatube на Django REST
Framework. Используються HTTP запросы GET, POST, PATCH, PUT и DELETE.

Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

git clone cd api_final_yatube

Cоздать и активировать виртуальное окружение:

python3 -m venv env source env/bin/activate

Установить зависимости из файла requirements.txt:

python3 -m pip install --upgrade pip pip install -r requirements.txt

Выполнить миграции:

python3 manage.py migrate

Запустить проект:

python3 manage.py runserver

Примеры запросов к API

api/v1/posts/:

GET - получить пост POST - добавить пост

api/v1/posts/{post_id}/comments/:

GET - получить комментарии POST - добавить комментарий
