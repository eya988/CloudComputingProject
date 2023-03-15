# CloudComputingProject
##
This is a web-based task manager that enables you to monitor both pending and completed tasks. Its creation was motivated by the desire to acquire knowledge on utilizing Docker Compose, a tool that allows for the simultaneous operation of multiple containers and inter-container communication.

### Requirements
1. Nodejs
2. Docker
3. Docker compose
4. Mongodb

### Steps to create docker images and running the project in a docker container
1. Open working folder in the terminal
2. Build the container and start it
```Shell
docker-compose up --build
```
Or you can also 
2. Build the image 
```Shell
docker compose build 
```
3. Then create and start the container 
```Shell
docker compose up
```
### List volumes 
List volumes: 
```shell
docker volume ls 
```

### Shut down container
Shut down container
```shell
docker-compose down
```
