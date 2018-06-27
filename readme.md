<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Dockerized Laravel 5.6

Some other commands you’ll be running often in a Laravel project:

## Create a throwable composer
`docker run --rm -v $(pwd):/app composer install`

## config .env
`cp .env.example .env`

## bring up laravel and all services
`docker-compose up`

## APP key
`docker-compose exec app php artisan key:generate`

## Set permission

`sudo chmod -R 777 bootstrap/cache/`

`sudo chmod -R 777 storage/`

## Check the site
`localhost:8080` 

## Enjoy!
