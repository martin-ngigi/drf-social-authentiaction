## INSTALLATIONS
```
pip install django
pip install djangorestframework
pip install djangorestframework-simplejwt
pip install google-api-python-client
pip install facebook-sdk
pip install python-twitter
```

- Link: 
- [Github](https://www.youtube.com/watch?v=d7OxfJZOIhQ&t=10s)
- [Youtube](https://github.com/CryceTruly/incomeexpensesapi)

- Enable Google credentials
- [Link](https://console.cloud.google.com/apis/credentials/consent?project=social-authentiaction)

- Create Meta App for facebook
- [Link](https://developers.facebook.com/apps)

- Twitter
- [Link](https://developer.twitter.com/en/portal/apps)

- Run server
```
source .venv/bin/activate
cd project
python3 manage.py runserver
```

- Run migration
```
source .venv/bin/activate
cd project
python3 manage.py makemigrations
python3 manage.py migrate
```