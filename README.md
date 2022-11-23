# recipe-app-api
Recipe project.

# Login docker
- docker login

# Docker build image
- docker build .

# Docker-compose build image
- docker-compose build

# Run flake8
- docker-compose run --rm app sh -c "flake8"

# Run test
- docker-compose run --rm app sh -c "python manage.py test"

# Add Django app via docker-compose
- docker-compose run --rm app sh -c "django-admin startproject app ."
