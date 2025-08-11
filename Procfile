web: gunicorn my_site.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn my_site.wsgi