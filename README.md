# docker-seat-pathfinder
A custom Docker-Compose for deploying EVE SeAT + Pathfinder.

## Attributions

- Basis for the Pathfinder Dockerfile: [KryptedGaming](https://github.com/KryptedGaming) / [pathfinder-docker](https://github.com/KryptedGaming/pathfinder-docker)

- Pathfinder portion of `nginx.conf`: [exodus4d](https://github.com/exodus4d) / [pathfinder.conf](https://gist.github.com/exodus4d/791f2742e6b2ee5ef481)

- Much of `docker-compose.yaml`: [eveseat](https://github.com/eveseat) / [seat-docker](https://github.com/eveseat/seat-docker)

## Building the image
```
docker build --build-arg VERSION=master -t pathfinder:dev -f ./pathfinder/Dockerfile
```