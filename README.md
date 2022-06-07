## steps

laravel basic app

- composer create-project laravel/laravel laravel8 8.0
- composer require laravel/ui
- php artisan ui bootstrap
- php artisan ui bootstrap –auth
- npm install
- npm run dev
- change user model migration

## pusher 
- uncomment // App\Providers\BroadcastServiceProvider in config/app.php
- BROADCAST_DRIVER=pusher in .env
- composer require pusher/pusher-php-server
- setup pusher creditioal in env
- npm install
- npm install --save laravel-echo pusher-js
- uncomment echo code segment in resources/js/bootstrap.js