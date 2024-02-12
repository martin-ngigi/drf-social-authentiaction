# Setting up the environment on Mac
- Create a directory  and navigate to directory
```
 mkdir drf-social-authentiaction
 cd drf-social-authentiaction
```
- create a virtual environment and activate it
```
python3 -m venv .venv
source .venv/bin/activate
```
- Install pip and django
```
 python3 -m pip install --upgrade pip
 python3 -m pip install django
```
- Start project and navigate to directory
```
django-admin startproject project
```
- Run server
```
source .venv/bin/activate
python3 manage.py runserver
```
- Create apps
```
python3 manage.py startapp auth
```