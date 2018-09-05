Docker and Kubernetes on a Raspberry Pi.

# Docker-and-Kubernetes

## Installation
Taken from https://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/

Start the Docker installer: 

> $ curl -sSL https://get.docker.com | sh

Set Docker to auto-start:

> $ sudo systemctl enable docker

Start the Docker daemon:

> $ sudo systemctl start docker

The Docker client can only be used by root or members of the docker group. Add pi or your equivalent user to the docker group:

> $ sudo usermod -aG docker pi

> $ docker version

> $ docker run hello-world

## Docker run commands:
> $ docker run busybox echo hello, world

> $ docker run busybox pwd

> $ docker run busybox ping 8.8.8.8

List running containers:
> $ docker ps

List all containers that have run:
> $ docker ps --all
