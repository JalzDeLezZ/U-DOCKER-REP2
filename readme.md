$ docker volume create poke-vol

$ docker compose up -d

$ docker compose down

$ docker compose logs
$ docker compose logs -f


<!-- Clear all -->
$ docker container prune
$ docker volume prune
$ docker network prune
$ docker image prune

DOCKER:
    mongodb://localhost:27018/admin