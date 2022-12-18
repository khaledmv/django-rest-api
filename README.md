# django-rest-api
Recipie Api With Django 


// Docker code snipets

docker-compose run --rm app sh-c "python manage.py collectstatic"

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ." 
