## First Laravel Api

This is my first laravel project

-   Laravel version : 9.6.0
-   PHP version : 8.1.4
-   Database : sqlite

## How to install Laravel

-   PHP install : `brew install php`
-   composer install : `brew install composer`
-   Laravel install : `composer create-project laravel/laravel first-laravel-api`
-   Start server : `php artisan serve`
-   Make Model & migration : `php artisan make:model Product --migration`, `php artisan migrate`
-   Make Controller : `php artisan make:controller ProductController --api`
-   Sanctum install : `composer require Laravel/sanctum`
-   Sanctum migration : `php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"`
