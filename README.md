# Docker container management with Traefik v2 and Portainer

A configuration set-up for a Traefik v2 reverse proxy along with Portainer and Docker Compose.

This set-up makes container management & deployment a breeze and the reverse proxy allows for running multiple applications on one Docker host. Traefik will route all the incoming traffic to the appropriate docker containers and through the open-source app Portainer you can speed up software deployments, troubleshoot problems and simplify migrations.

Detailed explanation how to use this in my blog post:
[Docker container management with Traefik v2 and Portainer](https://rafrasenberg.com/posts/docker-container-management-with-traefik-v2-and-portainer/)

## How to run it?

```
$ git clone https://github.com/rafrasenberg/docker-traefik-portainer ./src
$ cd src/core
$ docker-compose up -d
```
