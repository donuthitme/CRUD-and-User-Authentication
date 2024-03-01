# CRUD-and-User-Authentication

## Create a virtual environment:
```
py -m venv (name)
cd (name)
cd .\Scripts
cd .\activate
```
### Install Django and mysqlclient
```
pip install django
pip install mysqlclient
```
#### Redirect to 2-crm-crud
```
cd 2-crm-crud
```
##### Migrate and Runserver
```
python manage.py migrate
python manage.py make migrations
python manage.py runserver
```
