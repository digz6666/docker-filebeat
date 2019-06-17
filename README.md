### build image
docker build -t ast_filebeat -f Dockerfile .

### run
docker-compose up

### run in background (detached mode)
docker-compose up -d

### stop
docker-compose down

# bash into container
docker exec -it ast-filebeat bash

# get container logs
docker logs ast-filebeat
