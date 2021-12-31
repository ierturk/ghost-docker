# ghost-docker
This repo can be used to easily deploy ghost with MariaDB as a database backend and Nginx as a reverse proxy with **docker**.

## Prerequisites
In order to run Ghost using this project, the following packages must be installed:
- docker
- docker-compose

## Instructions
Replace your own data within configurations and compose files.
```
git clone https://github.com/ierturk/ghost-docker.git
cd ghost-docker/nginx-ssl
docker-compose up -d
docker-compose down
cd ..
docker-compose up -d
```
____
Copyright © 2021 StarGate, Inc.
