# Note-Sharing
Note Sharing Web Application Using Django

PREREQUISITES

1.Python Version >> 3.7.8

2.Virtualenv setup

Features

1.A registerd user can access all the notes shared/added by the admin
2.Can download the pdfs
3.can request specific notes
4.Admin can handle all the feattures like adding/updating/deleting the notes/users and can have overall control.
5.sqlite3 database


How to Run this project?

Virtualenv Setup

python -m install virtualenv or pip install virtualenv  
virtualenv (environment_name)  
environment_name\Scripts\activate

Run Project

First Locate to project folder in cmd with virtual environment running  
pip install -r requirements.txt  
python manage.py makemigrations  
python manage.py migrate  
python manage.py createsuperuser  
python manage.py runserver
Paste this 127.0.0.1:8000 IP Address on any browser and it will start.127.0.0.1:8000/admin and enter your superuser's username/pass for django admin panel access
