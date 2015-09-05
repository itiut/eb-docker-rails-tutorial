Elastic Beanstalk + Docker + Ruby on Rails tutorial
====

## Development environment setup

### Requirements (OS X)
- docker
- docker-compose
- docker-machine
- virtualbox

### Run containers
```console
$ docker-compose up -d
$ docker-compose run web rake db:create
```
