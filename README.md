# Django
This Repo is for practicing while learning this framework.
Here I am using Django version 4.0 with Python 3.8.X version.
To check for version of python installed use `python3 --version`.
And to check for installed version of Django use `Python3 -m django --version`.
Here i have assumed you want to work with python3 and Django 4.0.

There might be an inherent issue in manage.py i.e in shebang line
it uses keyword 'python' instead of 'python3' to refer to version 3 of python.
So this can stop you from directly executing the manage.py script, thus verify
if you face any problem.

To initialise a new project use command `django-admin startproject project_name`
And to initialise a new app in the project use `./manage.py startapp app_name`
or `python3 manage.py startapp app_name` if you don't wanna execute manage.py.

Also you can use `tree` command to view the directory tree from 
the current direcotry as base.
To run the light-weight development server by Django use `./manage.py runserver`
or `./manage.py runserver PORT` where PORT will be the explicitly defined 
numberical value of port to run the server.
