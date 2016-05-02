## LaravelJadePHPServiceProvider
Adds Laravel 5 JadePHP view engine with [ronan-gloo](https://github.com/ronan-gloo) [Jade.php](https://github.com/ronan-gloo/jade-php).

## Installation

Require this package with composer:

```
composer require cve/laravel-jade-php
```

Add the ServiceProvider to the providers array in config/app.php:

```
'Cve\LaravelJadePHPServiceProvider',
```

## Usage

Create views as always but in Jade syntax

if `config('app.debug') == false` then you must run Artisan `php artisan view:clear` each time you have modify the dependence jade view (by `extends` or `include`)

## License

LaravelJadePHPServiceProvider is licensed under the [MIT license](http://opensource.org/licenses/MIT).
copied
