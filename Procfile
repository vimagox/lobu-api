web: newrelic-admin run-program gunicorn --pythonpath="$PWD/lobu" wsgi:application
worker: python lobu/manage.py rqworker default