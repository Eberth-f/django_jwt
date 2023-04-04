# django_jwt

## Python Setup

Python version: `3.11.2`

Install the `virtualenv` package:

```shell
pip install virtualenv
```

Create a new virtualenv:

```shell
virtualenv .venv
```

Activate the virtualenv:

```
source .venv/bin/activate

or

.venv/Scripts/activate.bat

or

.venv/Scripts/activate.ps1
```

Install python project requirements:

```shell
pip install -r requirements.txt
```

## Project Setup

Create a new Django project:

```shell
django-admin startproject <project_name>
```

Create a new Django application:

```shell
django-admin startapp <application_name>
```

Run migrations:

```shell
python manage.py migrate
```

Create superuser:

```shell
python manage.py createsuperuser
```

Execute Django server:

```shell
python manage.py runserver
```

# TODO : Add other run configurations Here

Create admin user for Django Management:

```shell
python manage.py createsuperuser
```

## Postgres psql command line options

* Connect in database: `\c <databasE_NAME>`
* List databases: `\l`
* List tables in database: `\dt`
* List tables in database schema: `\dt <schema_name>.*`
* Describing a particular table: `\d <table_name>`
* Discoery postgres version: `SELECT version();`
* Seeing the previously executed command: `\g`
* Enlisting all the available commands: `\?`
* List schemas in database: `\dn`

## References

* [Escrevendo seu primeiro app Django, parte 1](https://docs.djangoproject.com/pt-br/3.2/intro/tutorial01/)
* [Writing custom django-admin commands](https://docs.djangoproject.com/en/3.0/howto/custom-management-commands/)
* [Django models and multiple databases](https://www.webforefront.com/django/modelmultidatabases.html)