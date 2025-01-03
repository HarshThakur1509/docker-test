# commands

docker run -d(detach mode) -p3001:3000(host's port: container's port) --name {Name}(assign custom name to image) {image} (pulls and starts the image)

docker start {id}(id number of container) (start a container)

docker stop {id}(id number of container) (stop a container)

docker ps -a(all containers) (shows all containers)

docker images (shows all images)

docker exec -it(interactive terminal) {id} /bin/bash (operates on container's linux terminal)

docker-compose -f {file} up ()

docker build -t {image} .(location of Dockerfile)
