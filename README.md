# Building Microservices with Node, Docker and Nginx
1. What is a Microservice
2. How do we make one?
3. How do we make them work together?

## Rule of thumb thoughts
Docker containers = good for almost all project sizes
Microservices = good for big companies with a lot of code and people
Sweetspot = Monolith app and databases in containers

## Pre-requisites
1. Node & Npm 
2. Text Editor
3. Docker

## Install the NodeJs
Do the following instructions:
1. curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
2. sudo apt install nodejs
3. Verify the installation: `node --version` && `npm --version`

## Install Docker
1. Run the following instructions
2. sudo apt-get update
3. sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
4. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
5. sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
6. sudo apt-get update
7. sudo apt-get install docker-ce
8. sudo docker run hello-world

## Install Docker Compose:
1. sudo curl -L "https://github.com/docker/compose/releases/download/1.23.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
2. sudo chmod +x /usr/local/bin/docker-compose
3. To verify the installation: `docker-compose --version`

## PPT Link : https://docs.google.com/presentation/d/1QORD1Xil7QAQWuoGyxZGPbB1k7Q9mteqWeTbkDxcDbM/edit?usp=sharing