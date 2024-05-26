# Bank Security Console

This is an internal repository for employees of "Siyaniye" bank. If you have stumbled upon this repository accidentally, you will not be able to run it as you do not have access to the database. However, you are free to use the layout code or see how the database queries are implemented.

The security console is a website that can be connected to a remote database with visits and employee pass cards.

### How to Install

Python3 should already be installed. Then use pip (or pip3, if there is a conflict with Python2) to install the dependencies:

```
pip install -r requirements.txt
```

Then create a .env file in the project folder and write your data without quotes in the format:

```
HOST = database url

PORT = port number

NAME = database name

USER = username

PASSWORD = database password

SECRET_KEY = password for SECRET_KEY

DEBUG = DEBUG status in True or False format

ALLOWED_HOSTS = list of hosts
```

### Objective of the project

The code was written for educational purposes in the Django ORM online course at [dvmn.org](https://dvmn.org/).