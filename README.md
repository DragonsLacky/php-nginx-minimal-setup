# Miniman PHP with PHP-FPM and nginx container setup

## Prerequisites
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## How to use

- Clone this repository
- Go to the container directory
  ```
    cd container
  ```
- Start the containers using docker compose
  > Docker compose plugin
  ```sh
    docker compose up 
  ```
  > Docker compose standalone
  ```sh
    docker-compose up 
  ```

## Settings

Settings are loaded in to the containers from the `config` directory using volumes

### PHP

To modify php settings create a new .ini file inside `config/php` directory and restart the containers

### Nginx

nginx.conf file can be modified directly and restart containers
