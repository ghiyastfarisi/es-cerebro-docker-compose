# es-cerebro-docker-compose

## dependencies 
1. docker with docker-compose 

## how to ?

1. clone cerebro from [https://github.com/lmenezes/cerebro](https://github.com/lmenezes/cerebro)
2. run cerebro build image inside cerebro folder `docker build -t cerebro:development .`
3. create docker network using name local_docker_network `docker network create local_docker_network`

## how to run ?

1. cd to root docker-compose folder
2. run all containers `docker-compose up -d`
3. run cerebro only `docker-compose up -d cerebro`
4. run elasticsearch service only `docker-compose up -d elasticsearch`
