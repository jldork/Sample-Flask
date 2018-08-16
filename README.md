Flask Sample
====================

## Development Setup
* `virtualenv venv`

* `source venv/bin/activate`

* `pip install -r requirements.txt`

* `python app.py`

## Run
Set the PORT and SQLALCHEMY_DATABASE_URI environment variables

Run command ```gunicorn -b 0.0.0.0:$PORT app:app```

