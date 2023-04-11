# Handy-Scripts

## Docker 
- shell: `docker exec -it <CONTAINER_ID> /bin/bash`
- remove all containers: `docker rm $(docker ps -aq)`
- stop all containers: `docker stop $(docker ps -aq)`
- remove all volumes: `docker volume rm $(docker volume ls)`
