# Nginx PHP MySQL
Based on [nanoninja - docker-nginx-php-mysql](https://github.com/nanoninja/docker-nginx-php-mysql)
Docker running Nginx, PHP-FPM, MySQL, Memcached and Adminer(PHPMyAdmin).

## Prerequisite

[Install docker compose](https://docs.docker.com/compose/install) on your machine

## Mount the docker

```sh
docker-compose build --no-cache && docker-compose up -d
```

## Unmount the docker

```sh
docker-compose down -v
```

## Install the Drupal

Drupal is located in ./data/drupal
Access to http://locahost:8000 and launch the installation

## Access Adminer(PHPMyAdmin)

--> http://localhost:8080

## Configuration environment

The .env file in the root contains the environment variable, such as user and password for the database.
