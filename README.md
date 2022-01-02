# ghost-docker
This repo can be used to easily deploy ghost with MariaDB as a database backend and Nginx as a reverse proxy with **docker**.

## Prerequisites
In order to run Ghost using this project, the following packages must be installed:
- docker
- docker-compose

## Instructions
Replace your own data within configurations and compose files.
```
>> Clone Repo

$ git clone https://github.com/ierturk/ghost-docker.git
$ cd ghost-docker
$ cp template.env .prod.env

>> Replace your own data within .prod.env file and nginx/*.conf files

$ ./server.sh .prod.env init
$ ./server.sh .prod.env stop
$ ./server.sh .prod.env start
```
____
Copyright © 2021 StarGate, Inc.
