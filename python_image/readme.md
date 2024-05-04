# steps to create docker image
create file - Dockerfile - refer attached file ,this file do step by step procedure

used to build image -docker build -t #image_name .
ex:docker build -t app .
app-image name



create the container and run the container :
docker run image_name
ex: docker run app 

docker ps - show the present container

docker ps -l - all containers

# Doubts:how to share image ?

## save the image :
docker save -o D:\Shravtek\sample_docker\myapp.tar app

## load the image :
docker load -i D:\Shravtek\sample_docker\myapp.tar 

## run that image :
docker run app:latest

