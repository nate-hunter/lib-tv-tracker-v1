# iNDEMAND TV TRACKER - LIBRARY
- A personal project that utilizes a Django REST Framework backend with a React frontend.
- An app to help a User / Scheduler track and manage Library TV Seasons.
- A User logs in with email and password.
- A User will be able to perform CRUD actions on a Season.
- A User will be able to add a NOTE to a Season. A Note may indicate an error.


## PROJECT SETUP:
```bash
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

```
- register 'rest_framework' and 'api' app
- set up routing / urls



## PROJECT CHECKLIST:
[] Create environment
[] Create Django App
[] Create User
	[] Implement email login
[] Create Models

## Models
- User
- Studio
- Season
- Note


## Features:
- A DASHBOARD of "Total Seasons", "Released", "Errors"
- A SUMMARY TABLE that lists all seasons and is 'searchable / filterable / sortable'
- An individual Season page that lists its details and Notes, and where it can be updatable
- A User Profile page where a User can see its information and the Seasons the User is working on. 
- A NAVBAR that can be used to navigate the site as well as access relevant Resources.
