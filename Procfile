web: gunicorn config.wsgi:application
worker: celery worker --app=mysite.taskapp --loglevel=info
