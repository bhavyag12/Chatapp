Prepare Your Environment

$ python3 -m venv env

$ source env/bin/activate

Install Django and Pin Your Dependencies

(env) $ python -m pip install django

(env) $ python -m pip freeze > requirements.txt

(env) $ python -m pip install django

(env) $ python -m pip install -r requirements.txt

Set Up a Django Project

(env) $ django-admin startproject <project-name>
  
(env) $ django-admin startproject <projectname> .

Start a Django App
  
(env) $ python manage.py startapp <appname>

Starting the development server
  
(env) $ python manage.py runserver

