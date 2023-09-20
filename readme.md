
!! BACKEND IMAGE :
https://hub.docker.com/r/klerith/pokemon-nest-app

$ docker compose down && docker compose up -d

Cargar una semilla con la data inicial
http://localhost:3000/api/v2/seed

Consultar listado
http://localhost:3000/api/v2/pokemon?limit=20&offset=40

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

MONGO-EXPRESS
http://localhost:8080/

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


DATA BASE:
______________
    mongodb://localhost:27018/admin

WITH AUTH:
(if you had volume)
    $ docker volume rm <name>
_________________________________
    mongodb://user:password@localhost:27018

docker volume prune

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

$ docker volume create poke-vol

    $ docker compose down
    $ docker compose up -d
$ docker compose up

$ docker compose logs
$ docker compose logs -f


<!-- Clear all -->
$ docker container prune
$ docker volume prune
$ docker network prune
$ docker image prune
