# Docker 

## Docker Compose CLI

    docker compose up -d
    docker compose up -d --build
    docker compose watch
    docker compose down
    docker compose down -v
    docker compose stop
    docker compose logs
    docker compose ps
    docker compose config
    docker compose start
    docker compose restart
    docker compose build

## Docker Run CLI

    docker build -t <name> . # Build an image from a Dockerfile.
    docker run --name <name> -d -p <host-port>:<container-port> <image-name> # Run a container from an image.
    docker ps # List running containers.
    docker ps -a # List all containers.
    docker run -it --rm <image-name> /bin/bash # Start an interactive shell inside a container.

## Docker Hub Actions

```sh
docker tag docker/welcome-to-docker YOUR-USERNAME/welcome-to-docker
```

## Resource 

- [Docker Run](https://docs.docker.com/reference/dockerfile)
- [Docker Compose](https://docs.docker.com/reference/compose-file)