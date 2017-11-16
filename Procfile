web: gunicorn config.wsgi:application
worker: celery worker --app=taray.taskapp --loglevel=info
