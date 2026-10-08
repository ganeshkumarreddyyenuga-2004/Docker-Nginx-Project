# Docker Nginx Project

## Overview

This project demonstrates running an Nginx web server inside a Docker container.

##  Commands Used

docker pull ubuntu
docker run -it --name srv01 ubuntu /bin/bash
apt update
apt install nginx -y
nginx -v
docker commit srv01 ubuntu_nginx
docker run -it ubuntu_nginx /bin/bash

## Technologies

* Docker
* Ubuntu
* Nginx

## Skills Gained

* Docker Images
* Docker Containers
* Container Management
* Nginx Installation

## Outcome

Successfully created a custom Docker image with Nginx installed and verified web server functionality.
