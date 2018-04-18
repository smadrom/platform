
<h1 align="center">
  <br>
  <a href="https://orchid.software/"><img src="https://orchid.software/img/orchid.svg" alt="ORCHID" width="250"></a>
  <br>
  <br>
</h1>

<h4 align="center">Powerful platform for building a business application using the  <a href="https://laravel.com" target="_blank">Laravel</a> framework.</h4>

<p align="center">
<a href="https://travis-ci.org/orchidsoftware/platform/"><img src="https://travis-ci.org/orchidsoftware/platform.svg?branch=master"></a>
<a href="https://styleci.io/repos/73781385"><img src="https://styleci.io/repos/73781385/shield?branch=master"/></a>
<a href="https://packagist.org/packages/orchid/platform"><img src="https://poser.pugx.org/orchid/platform/v/stable"/></a>
<a href="https://packagist.org/packages/orchid/platform"><img src="https://poser.pugx.org/orchid/platform/downloads"/></a>
<a href="https://packagist.org/packages/orchid/platform"><img src="https://poser.pugx.org/orchid/platform/license"/></a>
<a href="https://t.me/orchid_community"><img src="https://img.shields.io/badge/chat-telegram-blue.svg"/></a>
  
</p>

## Introduction

Platform gives you a simpler and faster way to create professional-quality business applications for Laravel framework.  
Using application templates, saves the time and effort of building from scratch, without sacrificing the flexibility needed to create custom applications.


![screenshot](https://user-images.githubusercontent.com/5102591/38919428-37f6191a-42f9-11e8-892a-6f9b27e8d599.png)


## Official Documentation

Documentation can be found at [ORCHID website](http://orchid.software).

###### Simple screenshot:
![screenshot](https://user-images.githubusercontent.com/5102591/32980416-22ad653e-cc77-11e7-9fb9-4747b241270f.png)


## System requirements

Make sure your server meets the following requirements.

- Apache 2.2+ or nginx
- MySQL Server 5.7.8+ , Mariadb 10.3.2+ or PostgreSQL
- PHP Version 7.1.3+


## Installation

Firstly, download the Laravel installer using Composer:
```php
$ composer require orchid/platform
```

Install package

```php
php artisan orchid:install
```

Create your admin user
```php
php artisan make:admin admin admin@admin.com password
```

Run server
```php
php artisan serve
```

#### Usage

To view ORCHID's dashboard go to:
```php
http://localhost:8000/dashboard
```



## Change log

See [CHANGELOG](CHANGELOG.md).

## Security

If you discover security related issues, please email  [Alexandr Chernyaev](mailto:bliz48rus@gmail.com) instead of using the issue tracker.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
