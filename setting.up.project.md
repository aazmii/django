## Create virtual environment at given directory
```
pip install pipenv
```
```
pipenv shell
```

```
pipenv install django
```

## To see the package installed, run 
```
pip freeze
```
## Create a project within this folder
```
django-admin startproject <project_name> 
```
## Creating 'App' 
Project is consisted with one or multiple module called 'app', which servs different purpose. 
change the root directory first 
```
cd <project_name>
```
to create an app 
```
python manage.py startapp <app_name>
```
this will create <app_name> into <my_project>. now run the servver - 
```
python manage.py runserver
```
## Migration
make sure manage.py exists on root directory. 
to create migration, run  
```
python manage.py makemigrations
```
apply generated migration to the db : 
```
python manage.py migrate
```
## Admin
```
python manage.py createsuperuser
```
## note: 
on root folder- <br> 
Pipfile, Pipfile.lock -> environment is set <br> 
manage.py, another folder same name as root folder -> a  project <br> 
admin.py,model.py, views.py -> an app

# Django Project Files Overview
Follow [this](https://medium.com/django-unleashed/django-project-structure-a-comprehensive-guide-4b2ddbf2b6b8) link

