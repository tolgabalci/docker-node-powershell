# docker-node-powershell
Ubuntu based image with latest (auto-build) of Node. Plus Powershell, NVM, Yarn and Git.

[![DockerPulls](https://img.shields.io/docker/pulls/tolgabalci/node-powershell.svg)](https://registry.hub.docker.com/r/tolgabalci/node-powershell/)
[![DockerStars](https://img.shields.io/docker/stars/tolgabalci/node-powershell.svg)](https://registry.hub.docker.com/r/tolgabalci/node-powershell/)


This repository contains a Docker file to build a Docker image for a developer environment. Compatible as a VSCode Dev Container.

## Pull the image from Docker Repository
```
docker pull tolgabalci/node-powershell
```

## Run the image from Docker Repository

* You can use this image for your VSCode Dev Container or
* You can run it directly:
```
docker run -it tolgabalci/node-powershell
```

## Build your own version of the image
```
docker build --rm -t <hub-user>/node-powershell .
```

## Push your own version of the image to Docker Hub
$ docker push <hub-user>/node-powershell



