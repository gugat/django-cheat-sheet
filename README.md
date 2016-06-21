# django-cheat-sheet
Cheat sheet for Django 



### General

##### Installation
pip install django 

##### Start project
django-admin.py startproject _my-project_

```
my-project/
├── manage.py
└── superlists
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py

```

##### Run shell
	python manage.py shell

##### Version

```
>>> import django
>>> print(django.get_version())
```

##### Run server
	python manage.py runserver

### Fixtures
##### Load fixture
<pre>
python manage.py loaddata <i>fixturename</i>
</pre>

##### Dump data from model (to use it as fixture) 
<pre>
python manage.py dumpdata <i>applicationname</i>.<i>modelname</i>
</pre>

### Migrations
##### Run and Rerun migrations
	python manage.py migrate





