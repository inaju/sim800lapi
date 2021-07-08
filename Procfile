release: python manage.py migrate
web: gunicorn sim800lapi.wsgi:application --log-file - --log-level debug

