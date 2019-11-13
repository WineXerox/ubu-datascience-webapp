# ubu-datascience-webapp

pipenv install django

## install pipenv
python - m pip insatll pipenv --user
## install pipenv
pipenv install django
## start pipenv
pipenv shell
## start django web project
django-admin startproject webapp
cd webapp
python manage.py myapp
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
