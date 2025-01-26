# Laravel CMS using Vanilla PHP Views

This repository is copy of the simple [PHP CMS](https://github.com/codeadamca/php-cms) except the CMS has been converted to Laravel. 

## Installation

The CMS uses the public storage driver, make sure to update your `.env` file:

```php
FILESYSTEM_DRIVER=public
```

The database setup includes migrations and seeding. Run the following command to initialize the database:

```sh
php artisan migrate:refresh --seed
```

All user accounts will have the default password of `password`.

> Full tutorial URL:  
> https://codeadam.ca/learning/php-cms-laravel.html

*** 

## Repo Resources

* [Visual Studio Code](https://code.visualstudio.com/)
* [Laravel](https://laravel.com/)

<br>
<a href="https://codeadam.ca">
<img src="https://cdn.codeadam.ca/images@1.0.0/codeadam-logo-coloured-horizontal.png" width="200">
</a>
