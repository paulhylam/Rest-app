# Catalog for Sports (and their items)
An item catalog example application written with Flask and sqlite3 for the assginemtn at Udacity.

It provides:
* User authentication with Gmail
* Item lists by categories.
* JSON API for catalogs
* All Users can read but signed in users can alter items they create/own

## Requirements
* Python 2.7
* SQLite 3.9
* Flask 0.9
* SQLAlchemy 1.0.12
* client_secrets.json from Google+

## Usage
* Download (or clone) the [repository](https://github.com/sbagdat/catalogr)
* To create database:
```
  python database_setup.py
```
* To populate database with seed data:
```
  python db_initialize.py
```
* Run the application:
```
  python project.py
```
* Navigate to http://localhost:5000
