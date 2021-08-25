# curly-doodle

## About Project LAPPLD
Linux Apache Postgresql PHP Laravel Docker

Dockerized laravel boilerplate

- [Permissions](https://stackoverflow.com/questions/30639174/how-to-set-up-file-permissions-for-laravel)
- [Dockerized Laravel Tutorial](https://www.twilio.com/blog/get-started-docker-laravel)
- [phpStorm doesnt see directories bug solution](https://stackoverflow.com/questions/48065971/phpstorm-not-showing-project-files-in-project-view)

## Docker Commands

- docker images
- docker ps
- docker rmi $(docker images)
- docker rm $(docker ps -a -q)
- docker-compose down
- docker-compose exec php-apache /bin/bash
- docker run -p 7000:7000 -d 71533a53a3d7
- docker exec -it dockerized-laravel sh
- docker-compose up -d --build
- docker-compose exec database /bin/bash

## Quick Start up

- http://localhost:8080/
- chmod -R 777 /var/www/laravel_docker/storage/logs/
- chmod -R 777 /var/www/laravel_docker/storage/framework/sessions/
- php artisan migrate:fresh --seed
- psql -U postgres laravel_docker
- SELECT * FROM quotes;