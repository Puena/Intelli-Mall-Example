# Intelli-Mall

## High-level view of the components

![Intelli-Mall Architecture](https://github.com/LordMoMA/Intelli-Mall/assets/67067729/097cfc9d-8d45-48fc-afda-a052d03eb96a.png)

## Intelli-Mall AWS Architecture

![Intelli-Mall AWS Architecture](https://github.com/LordMoMA/Intelli-Mall/assets/67067729/176f52d6-8bf4-4bb4-bdb6-15ea9ef5a836.png)

## How to start the application

Starting the monolith:

```bash
docker compose --profile monolith up
```

Starting the microservices

```bash
docker compose --profile microservices up  
```

> Note: my local machine is Mac M2 ARM64, be sure to locate the docker image with the tag version compatible with your machine architecture.
