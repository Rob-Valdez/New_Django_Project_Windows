# New_Django_Project_Windows

Install Anaconda from website

Add anaconda env object path to use "python"

Add Scripts, and Library/bin env object path to use "pip"

install Pipenv

install Git

create project directory

activate virtual env shell (pipenv shell)

pip install Django

django-admin startproject [projectname]

python manage.py runserver

open browser and check for validation

python manage.py startapp hello_world

in settings.py add hello_world to installed apps

create view

create templates folder

create template

add app urls to project

create app url

create env variable from django secret key

python manage.py runserver

initiate git in project directory

stage files in git

create github repo

commit files for change

git remote add origin

git push -u origin master

pipenv install gunicorn

pipenv lock

install heroku cli tool (https://devcenter.heroku.com/articles/getting-started-with-python#set-up)

heroku create

create Profile for project
must be on same path as manage.py
add "web: gunicorn [projectname].wsgi --log-file -" to Procfile

create requirements.txt
add 
"
django
gunicorn
"

git push heroku master
