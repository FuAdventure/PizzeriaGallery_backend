## Pizzeria Gallery Backend Server
This server is powered by Django3 and SQLite. 

You can clone this repo, install all dependencies from requirements.txt, create a database and then and run it at your local server.
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

API can be accessed at base_url = http://localhost:8000/api. A deployed version can be view here. 
- List view of Pizzeria records in the SQLite database: base_url
- Detail view of a record with it id number: base_url/id/
- Update an existing record: base_url/update/id/
- delete an existing record: base_url/delete/id/
- Create a new record: base_url/create/
- Administration portal: http://localhost:8000/admin (You need create a superuser to access administration operations, use python manage.py createsuperuser)
