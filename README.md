# Django-Django-REST-Framework-and-Docker
Django, Django REST Framework, and Docker. This is part of teaching project to my students to build RESTful API with Django, Django REST and Docker.

$ mkdir django-rest-docker && cd django-rest-docker
$ mkdir app && cd app
$ python3 -m venv env
$ source env/bin/activate

(env)$ pip install django==4.1.7 djangorestframework==3.14.0
(env)$ django-admin startproject drf_project .
(env)$ python manage.py startapp movies
