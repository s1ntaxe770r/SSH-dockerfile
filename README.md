# SSH-dockerfile

This Dockerfile creates an ssh service inside a docker container


* default user and password is test

i also wrote about it [here](https://dev.to/s1ntaxe770r/how-to-setup-ssh-within-a-docker-container-i5i)


## Building the image


` docker build -t IMAGE_NAME ` 

## Runing the image 

` docker run IMAGE_NAME -p 22:22 `
