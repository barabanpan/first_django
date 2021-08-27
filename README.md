# Polls app by [tutorial](https://docs.djangoproject.com/en/3.2/intro/tutorial01/).

# To run
1. Install PostgreSQL: [tutorial](https://www.digitalocean.com/community/tutorials/postgresql-ubuntu-16-04-ru).
2. ```pip install -r requirements.txt```
3. ```sudo apt-get install python3-django```
4. Create in `mysite` folder .env file:
```
DB_NAME=<db_name>
DB_USER=<db_user>
DB_PASSWORD=<db_password>
DB_HOST=127.0.0.1
DB_PORT=5432

SECRET_KEY=<some_secret_key>

DEBUG=True
```
5. ```python manage.py runserver```
