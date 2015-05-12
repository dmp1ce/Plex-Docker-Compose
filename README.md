# Plex Media Server

This is a Docker Compose configuration which will download and install Plex Media Server.

## Prerequisites

- [Docker](http://docs.docker.com/installation/#installation)
- [Docker Compose](http://docs.docker.com/compose/)

## Usage

`docker-compose up -d` to start Plex.

Use `http://localhost:32400/web/index.html` to view the Plex application. Put your media in the `data` directory or modify the `docker-compose.yml` configuration to add your own media directory. For instance, you could add:

```
volumes:
  - /mnt/my_nas_server:/mnt/my_nas_server
```
