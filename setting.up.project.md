## Create a folder and the in vs code. Run following commands to create project 
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
## To run django project 
```
django-admin startproject <project_name> 
```
# Django Project Files Overview

### 1. `__init__.py`
- **Purpose**: Marks the directory as a Python package.
- **Functionality**: Enables Python to recognize the directory as a module, allowing imports across the project.

### 2. `asgi.py`
- **Purpose**: Configures the **ASGI** (Asynchronous Server Gateway Interface) settings for the project.
- **Functionality**:
  - Sets up the environment for asynchronous handling of requests.
  - Acts as the entry point for ASGI-compatible web servers.

### 3. `settings.py`
- **Purpose**: The core configuration file of the Django project.
- **Functionality**:
  - Contains project settings such as database configurations, installed apps, middleware, templates, and static files.
  - Used to control project behavior and environment-specific customizations.

### 4. `urls.py`
- **Purpose**: Defines URL patterns for the project.
- **Functionality**:
  - Maps URLs to their respective views or endpoints.
  - Serves as a central routing mechanism for the application.

### 5. `wsgi.py`
- **Purpose**: Configures the **WSGI** (Web Server Gateway Interface) settings for the project.
- **Functionality**:
  - Acts as the entry point for WSGI-compatible web servers like Gunicorn or uWSGI.
  - Helps in deploying the Django project in a production environment.

### 6. `manage.py`
- **Purpose**: A command-line utility for administrative tasks.
- **Functionality**:
  - Provides commands to manage the Django application, such as starting a development server, migrating databases, or creating new apps.
  - Acts as an interface to `django-admin`.

