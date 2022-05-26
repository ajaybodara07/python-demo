# python-demo

## Installation

Install the required dependencies::

    pip install -r requirements.txt

Apply migrations:

    python manage.py migrate

Add your Phrase Project ID to ``settings.py``::

    PHRASE_PROJECT_ID = 'PHRASE_PROJECT_ID'

Start the django application::

    python manage.py runserver

