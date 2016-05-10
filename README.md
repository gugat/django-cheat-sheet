# django-cheat-sheet
Cheat sheet for Django 

### General
##### Run shell
	python manage.py shell

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





