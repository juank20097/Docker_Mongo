# Docker_Mongo
This is a Repository with configuration to deploy Mongo DB and Mongo Express

it's very important that you install docker before applying this manual. if you don't have a Docker. check Install Docker on Ubuntu and continue with the steps

# Install Docker in Ubuntu X.X

1.- Update Repositories

sudo apt update

2.- Avaible packages with HTTP

sudo apt install apt-transport-https ca-certificates curl software-properties-common

3.- Add Key GPG to Docker

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

4.- Add Docker Repository in source.list

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

5.- Update Repositories

sudo apt update

6.- Check Docker Repository

apt-cache policy docker-ce 

7.- Install Docker

sudo apt install docker-ce

8.- Check docker service

sudo systemctl status docker


# Deploy Docker Mongo and Mongo-Express 

# Option Docker Compose

This Option is Easy

1.- Check your docker-compose 

docker-compose --version

2.- Run docker compose with the yml file

docker-compose -f mongo.yml up

3.- Check your docker in your web browser with http://localhost:8081

 
