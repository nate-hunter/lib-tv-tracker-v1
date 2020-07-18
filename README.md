PROJECT SETUP:
$ cd Workspace/
$ cd tv-tracker-api/
$ python -m venv venv
$ source venv/Scripts/activate
=>(venv)
$ pip install Django
$ pip install Djangorestframework
$ pip freeze  # To check installed correct
$ django-admin startproject lib_tv_tracker .
$ django-admin startapp api
$ python manage.py runserver  # To check if server is running and the project is set up correctly
$ git init



PROJECT CHECKLIST:
[] Create environment
[] Create Django App
[] Create User
	[] Implement email login
[] Create Models
