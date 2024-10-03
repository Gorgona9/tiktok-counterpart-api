# Tiktok Counterpart API (tiktok-like backend)

### Learn how to build this!

## NOTE

### For this Tiktok Counterpart API to work you'll need the Frontend:

Tiktok Clone: https://github.com/Gorgona9/tiktok-counterpart

## App Setup

```
git clone https://github.com/Gorgona9/tiktok-counterpart-api.git
```

Then
```
composer install 

cp .env.example .env 

php artisan cache:clear 

composer dump-autoload 

php artisan key:generate

composer require laravel/breeze --dev

php artisan breeze:install (FOR THIS SELECT THE API INSTALL)

php artisan serve
```

Create a DATABASE and then run this command
```
php artisan migrate
```
