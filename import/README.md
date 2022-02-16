# Docker container for running rust

### Starting the container
Open a cmd to this folder. Edit the volume that must be mounted inside the container.  
```
docker-compose up -d
```
will bring up the container.

### Running a shell inside the container
Run
```
docker exec -it <mycontainer> bash
```
where <mycontainer> is a part of the container id obtained by ```docker ps```
