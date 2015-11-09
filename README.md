# Docker Geonetwork

Geonetwork 3.0 Docker image.

This image is based in eliotjordan/geonetwork-docker Dockerfile.

## Building image cloning this repository
Build image and run container (cloning this Git repository):

```bash
$ git clone https://github.com/GeographicaGS/Docker-Geonetwork.git
$ cd Docker-Geonetwork
$ docker build -t geographica/geonetwork .
$ docker run --name geonetwork -itd -p 8888:8080 geographica/geonetwork
```
