# Project setup

## Packages setup
```bash
$ pip install flask_login flask_wtf
```

## Database setup
```bash
$ pip install flask-sqlalchemy
$ pip install flask-migrate
```

## Make migrations
```bash
$ flask db upgrade
```

## Run server
```bash
$ export FLASK_APP=microblog.py
$ flask run
```