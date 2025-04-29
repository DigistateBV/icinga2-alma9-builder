# Building Icinga2 rpm packages for Alma9

## Build using Docker
The container needs at least 8GB of RAM.

To build the rpm, run the following commands:
```
docker run --privileged .
```
The rpm files are in `/root/rpmbuild/RPMS/` inside the container.

## Build using docker compose
Use the docker compose file to build the rpm:
```
docker compose up --build
```
The rpms will be in the `result` directory.
