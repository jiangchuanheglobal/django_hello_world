# django, postgresl quick setup
```
#! /bin/bash

python3 -m venv venv
source venv/bin/activate
python --version
pip install django
django-admin startproject myproject
cd webapp
cd myproject
python manage.py runserver
docker-compose up -d
docker ps
docker logs -f xxx
python manage.py migrate
```
