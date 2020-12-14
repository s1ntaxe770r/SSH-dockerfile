# SSH-dockerfile

This Dockerfile creates an ssh service inside a docker container


![Docker](https://github.com/s1ntaxe770r/SSH-dockerfile/workflows/Docker/badge.svg)

* default user and password is test

i also wrote about why you'd want to do this here [here](https://dev.to/s1ntaxe770r/how-to-setup-ssh-within-a-docker-container-i5i)


## Building the image


` docker build -t IMAGE_NAME ` 

## Runing the image 

` docker run IMAGE_NAME -p 22:22 `


## Or simply pull the image 

`docker pull ghcr.io/s1ntaxe770r/image:latest`

