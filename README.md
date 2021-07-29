ContactList Api

create a .env file in ContactApi subfolder & setup following variables:
JWT_SECRET_KEY=
DJANGO_SECRET_KEY=

run:
python manage.py makemigrations
python manage.py migrate
python manage.py runserver