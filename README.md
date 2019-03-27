# es-cerebro-docker-compose

## dependencies 
1. docker with docker-compose 

## how to ?

1. clone cerebro from [https://github.com/lmenezes/cerebro](https://github.com/lmenezes/cerebro)
2. run cerebro build image inside cerebro folder `docker build -t cerebro:development .`
3. create docker network using name local_docker_network `docker network create local_docker_network`
4. run within docker-compose file `docker-compose up -d`
