## docker --version

shows docker current version

<img src="images/01" width="700" title="hover text">

## docker pull imbalakrishnan/welcome-app

pull images from docker hub

<img src="images/02" width="700" title="hover text">

## docker run -d -p 8000:8000 imbalakrishnan/welcome-app

create a container from an image and run the container


<img src="images/03" width="700" title="hover text">

## docker images

show list of docker images


<img src="images/04" width="700" title="hover text">

## docker ps

Shows list of running docker container
<img src="images/05" width="700" title="hover text">

## docker ps -a

show all the running and exited containers 

<img src="images/06" width="700" title="hover text">

## docker exec --help

show all the helpfull docker commands 

<img src="images/07" width="700" title="hover text">

## docker stop <container_id>

stops a running container

<img src="images/08" width="700" title="hover text">

## docker login

login into docker from terminal

<img src="images/09" width="700" title="hover text">

## docker rmi -f imbalakrishnan/welcome-app

delete an image from local storage

<img src="images/10" width="700" title="hover text">

## docker build -t flask-app .

 build an image from a specified docker file

<img src="images/11-1" width="700" title="hover text">
<img src="images/11-2" width="700" title="hover text">

## docker tag flask-app:latest imbalakrishnan/flask-app:latest

tag docker image locally

<img src="images/12" width="700" title="hover text">

## docker push imbalakrishnan/flask-app:latest

push docker image to docker hub

<img src="images/13" width="700" title="hover text">

## docker logs <container_id>

fetch logs of a container

<img src="images/14" width="700" title="hover text">

## docker info

displays system wide information regarding the Docker installation

<img src="images/15" width="700" title="hover text">
