## Pizzeria Gallery Backend Server
This server is powered by Django3 and SQLite. 

#### Steps for your adaptation:
1. Clone this repo
2. Run `pip install -r requirements.txt` to install all dependencies from requirements.txt
3. Run `python manage.py migrate` to create a database
4. Run `python manage.py runserver` to run it at your local server.

API can be accessed at base_url = http://localhost:8000/api. A deployed version can be view [here](http://www.pizzavspizza.com/api/). 
- List view of Pizzeria records in the SQLite database: base_url
- Detail view of a record with it id number: base_url/id/
- Update an existing record: base_url/update/id/
- delete an existing record: base_url/delete/id/
- Create a new record: base_url/create/
- Administration portal: http://localhost:8000/admin (You need create a superuser to access administration operations, run `python manage.py createsuperuser`)
