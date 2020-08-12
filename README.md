# photo-store
Photos and images store to render local cached from external API

# Installation
## Build Docker
```shell
$ git clone https://github.com/fernandezgarcete/photo-store.git
$ cd photo-store/
$ docker build .
```
## Create Django application
```shell
$ docker-compose run --rm app sh -c "django-admin.py startproject app ."
```
