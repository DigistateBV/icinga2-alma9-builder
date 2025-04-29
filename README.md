# Building Icinga2 rpm packages for Alma9

## Build using Docker
To build the rpm, run the following commands:
```
docker run --privileged .
```
The rpm files are in `/var/lib/mock/almalinux-9-x86_64/result` inside the container.

## Build using docker compose
Use the docker compose file to build the rpm:
```
docker compose up --build
```
The rpms will be in the `result` directory
