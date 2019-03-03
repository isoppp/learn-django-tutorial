# learn-django-tutorial

## setup(fish)

- python3 -m venv .venv
- source .env/bin/activate.fish
- pip install -r requirements.txt
- pre-commit install

## dev commands

- source .env/bin/activate.fish
- python manage.py runserver
- python manage.py makemigration APP
- python manage.py sqlmigrate 
  - dryrun?
- python manage.py migrate
- python manage.py test APP

