# docker
Docker is a containerization tool.

## Commands
### Version
docker -v
### Build
docker build .
docker build -t image-name .
### Run
docker run image-name
### List
docker ps
docker ps -a
docker ps | grep image-name
### Logs
docker logs image-name
docker logs image-name --tail 20

## Docker Compose Commands
### Build
docker compose build
docker compose build image-name
docker compose -f docker-compose.yml build
docker compose -f docker-compose.yml build image-name
### Run
docker compose up
docker compose up -d
docker compose up -d --build image-name
docker compose -f docker-compose.yml up
docker compose -f docker-compose.yml up -d
docker compose -f docker-compose.yml up -d image-name
### Shut down
docker compose down

