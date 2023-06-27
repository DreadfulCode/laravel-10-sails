# laravel-10-sails
Laravel 10 Sails Starter with Breeze, Inertia, Vue 3, Postgres 15, and Mailpit

# Installation:

`cp .env.example .env`

`./vendor/bin/sail up -d`

`./vendor/bin/sail artisan vendor:publish`

`./vendor/bin/sail artisan migrate`

`./vendor/bin/sail artisan list`

Rebuild with:
`./vendor/bin/sail up --build`

# Unit Testing:

`./vendor/bin/phpunit tests`

# About

This boilerplate was created with the comigrammands:

`curl -s "https://laravel.build/tms?with=pgsql,redis,mailpit" | bash`

`cd tms && ./vendor/bin/sail up -d`

`./vendor/bin/sail composer require laravel/breeze --dev`

`./vendor/bin/sail artisan breeze:install vue`

`./vendor/bin/sail vue@next --save`

`./vendor/bin/sail artisan migrate`

`./vendor/bin/sail artisan vendor:publish --tag=laravel-assets --ansi --force`

