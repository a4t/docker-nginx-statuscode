# docker-nginx-statuscode

```
$ docker-machine create --virtualbox-cpu-count "1" --virtualbox-memory "1024" --driver virtualbox default
$ eval $(docker-machine env default)
$ docker-compose up -d
$ curl $(docker-machine ip default):40000
error 500
```
