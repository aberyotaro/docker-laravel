# docker-laravel

## procedure

1. git clone https://github.com/aberyotaro/docker-laravel.git
1. docker-compose up -d
1. cd src
1. git clone https://github.com/laravel/laravel.git .
1. docker-compose exec app ash
1. composer install
1. cp .env.example .env
1. php artisan key:generate

