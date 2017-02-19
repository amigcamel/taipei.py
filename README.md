taipei.py
===================
A mezzanine-based blog for Taipei.py


----------


Demo
-------------
https://taipei-py.herokuapp.com

Dependencies
-------------
Python 3.5.2  
Django 1.8.17  
Mezzanine 4.2.2  

Installation
-------------
```
git clone https://github.com/amigcamel/taipei.py
cd taipei.py
pip install -r requirements.py
```

Deployment
-------------
In development:
```
python manage.py runserver
```
In production
```
gunicorn taipei_py.wsgi
```
