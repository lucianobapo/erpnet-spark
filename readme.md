<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.

## Learning Laravel

Laravel has the most extensive and thorough documentation and video tutorial library of any modern web application framework. The [Laravel documentation](https://laravel.com/docs) is thorough, complete, and makes it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 900 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Dev command
***First time run***
```shell
php artisan make:auth
npm install font-awesome --save-dev
php artisan vendor:publish --tag=erpnetWidgetResourceGulpfile
gulp --gulpfile=gulpfileErpnetWidgetResource.js
```

***Updating commits***
```shell
cd ~/code/erpnet-spark/packages/erpnet-delivery && git cmt
cd ~/code/erpnet-spark/packages/erpnet-migrates && git cmt
cd ~/code/erpnet-spark/packages/erpnet-models && git cmt
cd ~/code/erpnet-v5 && composer update

git cmt && ssh spark.ilhanet.com
cd ~/code/erpnet-spark/ && git pull && composer install && exit
```

## Production command
***First time run***
```shell
ssh spark.ilhanet.com
cd code/erpnet-spark/ && git pull && composer install && exit
```

***First time run***
```shell
rsync -rvztPhe ssh /home/luciano/code/erpnet-spark/.env.production spark.ilhanet.com:code/erpnet-spark/.env
php artisan vendor:publish --tag=erpnetWidgetResourceFonts --force
php artisan vendor:publish --tag=erpnetMigratesMigrations --force
sudo ./permissions.sh
cd ~/code/erpnet-spark && php artisan migrate
```
