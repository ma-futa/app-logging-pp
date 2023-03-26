application logging process playground
aim: produce a solution for application logging for client applications running on 
- docker swarm
- AKS cluster

info:
all applications have been fitted with docker logger and so their logs can be accessed using  
$ docker container logs <container-id>
$ docker service logs <service-id>
