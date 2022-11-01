
## Build image
```
mkdir docker
#Move dockerfile and any associated files into directory 
cd docker
docker build . -t mydocker/latest
 ```
 
 ## See all docker images
 ```
 docker images
 ```
 
 ## See all running containers
 ```
 docker ps
 ```
 
 ## Remove dangling images
 ```
 docker image prune
 ```
 
 ## Remove all stopped containers
 ```
 docker container prune
 ```
 
## Run container interactively so that you can enter it 
```
docker run -it --rm --entrypoint "/bin/bash" <docker-image-name>
```

