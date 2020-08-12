# photo-store
Photos and images store to render local cached from external API

# Installation
## Init Docker
```shell
$ git clone https://github.com/fernandezgarcete/photo-store.git
$ cd photo-store/
$ docker build .
```
## Apply Django Migrations
```shell
$ docker-compose run --rm app sh -c "python manage.py migrate"
```
## Run Server
```shell
$ docker-compose up
```
