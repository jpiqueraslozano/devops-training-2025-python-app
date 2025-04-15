##necesitamos una máquina linux o (windows con podman)
##tiene que estar instalado docker, python, docker-compose

# Developer Use Guide

## Run app
```bash
 docker build -t my-app:0.0.1 .
 docker run -d --name app1 -p 8040:5000 my-app:0.0.1
 docker exec -it app1 bash
 docker stop app1
 docker start app1
 docker logs app1

```
