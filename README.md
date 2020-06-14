# Codeigniter

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]][link-license]
[![Total Downloads][ico-downloads]][link-downloads]

This is a library that provides the core functionality (the "system" folder) of the [Codeigniter](http://www.codeigniter.com/) framework that might can be useful for testing framework-related libraries.

## Installation

Install `Codeigniter` via [Composer](https://getcomposer.org/):

``` bash
$ composer require rougin/codeigniter
```

To create a new project, install [Ignite](https://github.com/rougin/ignite) instead:

``` bash
$ composer create-project rougin/ignite "project-name"
```

## Why?

### One-command update

I just need to run the `composer update` command to update the framework's core functionalities.

### Out of curiosity

I want to create an installer for Codeigniter's core using `composer require` command only.

### Simplify unit testing

Together with [Spark Plug](https://github.com/rougin/spark-plug), you can easily create Codeigniter instances in your test cases.

## Ignite project

Ignite is a [Composer](https://getcomposer.org/)-based project for the [Codeigniter](http://www.codeigniter.com/) framework which has a different structure of the "application" folder compared to the [original](https://github.com/bcit-ci/CodeIgniter/tree/develop/application). It was created to demonstrate the convenience of using the Composer-based Codeigniter packages in creating new applications.

### Folder Structure

``` bash
new-application/
├── cache/
├── config/
├── controllers/
├── core/
├── helpers/
├── hooks/
├── language/
├── libraries/
├── logs/
├── models/
├── third_party/
├── vendor/
├── views/
├── web/
│   ├── user_guide
│   ├── .htaccess
│   └── index.php
└── composer.json
```

## License

The MIT License (MIT). Please see [LICENSE][link-license] for more information.

[ico-version]: https://img.shields.io/packagist/v/rougin/codeigniter.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/rougin/codeigniter.svg?style=flat-square

[link-downloads]: https://packagist.org/packages/rougin/codeigniter
[link-license]: https://github.com/rougin/codeigniter/blob/master/LICENSE.md
[link-packagist]: https://packagist.org/packages/rougin/codeigniter