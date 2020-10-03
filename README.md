# Azure-Docker-Kubernetes

TO be used for Reference for Docker
Kubernetes etc.

Docker commands
docker ps

Docker run - docker create + docker start
docker logs pid
docker stop containerid
docker exec -i -t containerid sh

publish image to docker hub
docker build -t amit/redis:latest .

docker run amit/redis

https://howtodoinjava.com/java/library/docker-hello-world-example/
https://www.youtube.com/watch?v=wi-MGFhrad0
https://www.youtube.com/watch?v=FlSup_eelYE
https://www.youtube.com/watch?v=VZdwv134Klw

Docker Commands
FROM
RUN
CMD 

docker run hello-world
docker --version
docker-machine ip
docker images

Building Image
docker build -f /path/to/a/Dockerfile .

docker build -t shykes/myapp .

Tag into multiple repositories
docker build -t shykes/myapp:1.0.2 -t shykes/myapp:latest .


docker build -t staramitks/springboot:1.0.0 -t staramitks/springboot:latest

docker run -d -p 8080:8080 -t staramitks/springboot
