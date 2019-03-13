# docker-compose-socks5

## Description

Simple implementation of socks5 proxy protocol using Scala & Netty.
Fully using asynchronous java NIO to scale with many concurrent connections.

Intended to be deployed with docker on private vps for quick setup.

Docker Hub: https://hub.docker.com/r/dijedodol/simple-socks5-server/

Image GitHub: https://github.com/dijedodol/simple-socks5-server

## Install

```
cp .env.dist .env
```

Edit variable SSS_USERNAME and SSS_PASSWORD

## StartUp

```
docker-compose up -d
```
