![Docker Build](https://github.com/ASalonio/docker-r-studio/actions/workflows/docker.yml/badge.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/augusto93921/docker-r-studio)

# docker-r-studio

R-Studio in a container

## Description

To allow usage of R-Studio in a portable way using Docker Container
The image is automatically built and published to Docker Hub using GitHub Actions.

## Procedure

### Build Image

`docker login`- to authenticate
`docker build -t augusto93921/docker-r-studio .`

### Run Container

`docker run --rm -p 8787:8787 -e PASSWORD=guest -v C:/UDEMY/R_Studio_Shared:/home/rstudio/R_Studio_Shared augusto93921/docker-r-studio`

### Stop Container

`CTRL + C`

### Push Image to Docker Hub

` docker push augusto93921/docker-r-studio`







