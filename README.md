# Simple Django App
This is a simple, minimal Django app intended to help understand the main aspects of working with Django. Also, this application has a Dockerfile and its public image is on DockerHub and deployment.yml and service.yml files can be used to deploy this application using Kubernetes.

## Usage Instructions
Clone this repository e.g.

```
git clone git@github.com:nishankkoul/simple-django-app.git
```

Navigate to the 'cool_counters' Django project:

```
cd simple-django-app/cool_counters
```

Run migrations to update/create database
```
python manage.py migrate
```

Run the Django development server
```
python manage.py runserver


```

Navigate to to http://127.0.0.1:8000
