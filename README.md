# Docker 

## Docker Compose CLI

    1. docker compose up -d
    2. docker compose up -d --build
    3. docker compose watch
    4. docker compose down
    5. docker compose down -v
    6. docker compose stop
    7. docker compose logs
    8. docker compose ps
    9. docker compose config
    10. docker compose start
    11. docker compose restart
    12. docker compose build

## Docker Run CLI

    1. docker build -t <name> . # Build an image from a Dockerfile.
    2. docker run --name <name> -d -p <host-port>:<container-port> <image-name> # Run a container from an image.
    3. docker ps # List running containers.
    4. docker ps -a # List all containers.
    5. docker run -it --rm <image-name> /bin/bash # Start an interactive shell inside a container.