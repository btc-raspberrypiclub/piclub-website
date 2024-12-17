# BTC RaspberryPi Club Website

RaspberryPi Club Website in Django

## Building and developing

### Quickstart

1) clone the repo and cd into the folder
2) Build the image locally: `docker compose build`
3) Bring up the dtabase container: `docker compose up database_default -d`
4) Generate the tables and apply patches: `docker compose run --rm -it web python manage.py migrate`
5) Create a superuser to use: `docker compose run --rm -it web python manage.py createsuperuser`
6) Bring up the actual web engine: `docker compose up -d`

## Stuff we used to make our site engine

Here are some links to docs and sources of the tools, modules, etc that we used to make our website/application.  If/when we use/add more - we will add links to them here as well.

Docker

- https://docs.docker.com/manuals/

Github

- https://github.com/

Django

- Django: https://www.djangoproject.com/
- Package index for common published options: https://djangopackages.org/

Python (Django is build with Python)

- https://docs.python.org/3/
- https://pypi.org/

PostgreSQL (our database of choice for production)

- https://www.postgresql.org/

DjangoCMS (a Django plugin/module providing content management features)

-  https://user-guide.django-cms.org/en/latest/
-  https://docs.django-cms.org/en/latest/introduction/01-install.html

Django-material-kit (a nice theme to start with)

-  https://github.com/app-generator/django-material-kit
  -  https://github.com/app-generator/django-theme-material-kit

