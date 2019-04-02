# django-movie

1. the docker compose file is made of 2 docker image:
- postgres Image
- python 3 image with a django frame work. the image spec is in the Dockerfile in this directory

2. Run a command on the Docker
. To create project inside the web docker. run this sudo docker-compose 

	```sudo docker-compose run web django-admin startproject composeexample .```

#### References
- https://docs.docker.com/compose/django/
- https://github.com/tomaratyn
- Buulding Django 2.0 Web Applications
