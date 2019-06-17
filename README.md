### build image
docker build -t ast_filebeat -f filebeat/Dockerfile .

### run
docker-compose up

### run in background (detached mode)
docker-compose up -d

### stop
docker-compose down

### bash into container
docker exec -it ast-filebeat bash

### get container logs
docker logs ast-filebeat

### browse docker volume
docker volume inspect docker-filebeat_filebeat_data
cd #mount-point
