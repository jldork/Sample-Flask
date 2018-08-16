Flask Heroku Sample
====================

A simple Python Flask example application that's ready to run on Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Development Setup

* `pipenv install`

* `pipenv shell`

* `python app.py`

## Screenshot

![screenshot](https://i.imgur.com/wf74fxY.png)

## Deploy

* `heroku create`

* `heroku addons:create heroku-postgresql:hobby-dev`

* `git push heroku master`

* Note: make sure you run `db.create_all()` to create the tables.

## Contributors

* [Yefim](https://twitter.com/yefim)

## Run
Set the PORT and SQLALCHEMY_DATABASE_URI environment variables

Run command ```gunicorn -b 0.0.0.0:$PORT app:app```

