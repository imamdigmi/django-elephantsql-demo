# django-elephantsql-demo
DaaS using Django and ElephantSQL demo


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

# Run!
```bash
python manage.py runserver
```

Navigate to [localhost:8000](http://127.0.0.1:8000/)