release: cd network-api && python ./manage.py migrate --no-input && python ./manage.py heroku_release
web: cd network-api && gunicorn networkapi.wsgi:application
