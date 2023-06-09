
# graphene-django

## Examples from docs with bugs fixed

source: https://docs.graphene-python.org/

Two examples:  
1) cookbook  
2) relay

For both, a similar setup in each directory:
```
% python -m venv .venv
% source .venv/bin/activate
% pip install -r requirements.txt 
% python manage.py makemigrations
% python manage.py migrate
% python manage.py loaddata ingredients
% python manage.py runserver
```