# Docker-and-Kubernetes

## Installation
Taken from https://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/

Start the Docker installer

$ curl -sSL https://get.docker.com | sh

Set Docker to auto-start

$ sudo systemctl enable docker

Start the Docker daemon with:


$ sudo systemctl start docker

The Docker client can only be used by root or members of the docker group. Add pi or your equivalent user to the docker group:

$ sudo usermod -aG docker pi


$ docker version

$ docker run hello-world

