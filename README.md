  #Orchestrate Deployment
  213  docker-compose up

  #Inspect Containers are Attached to Default Docker Network
  253  docker network inspect mtglibrarydocker_default

  #Show all running containers
  260  docker-compose ps

  #Stop All Containers
  214  docker-compose stop

  #Remove Stopped Containers
  276  docker-compose rm   

  #List Images
  256  docker images
  #Remove Docker-Compose Images
  238  docker rmi -f mtglibrarydocker_spring-boot
  255  docker rmi -f mtglibrarydocker_elasticsearch
  #Remove Base Images
  270  docker rmi -f mtglibrary-spring:latest
  299  docker rmi -f elasticsearch:7.3.0
