# Django + ElephantSQL
DaaS (Data as a Service) using Django and ElephantSQL demo


![ElephantSQL Portal](elephantsql-portal.png)

## Setup
Activate virtual envirounment
```bash
pipenv shell
```

Install dependencies
```bash
pipenv install
```

Migrate Schema
```bash
python manage.py makemigrations && python manage.py migrate
```

Create Superuser for accessing Django Admin
```bash
python manage.py createsuperuser
```

Sample configuration
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'database_name',
        'USER': 'database_username',
        'PASSWORD': 'database_password',
        'HOST': 'databast_host',
        'PORT': 'database_port',
    }
}
```

# Run!
```bash
python manage.py runserver
```

Navigate to [localhost:8000](http://127.0.0.1:8000/)