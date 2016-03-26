# CodeIgniter

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]

Yet another way to install [CodeIgniter](http://www.codeigniter.com/) via [Composer](https://getcomposer.org/).

## Install

Via Composer

``` bash
$ composer create-project rougin/ignite "codeigniter"
```

If you want the latest updates, use ```rougin/codeigniter:dev-master```.

## Why?

### Out of curiosity

I want to create an installer for CodeIgniter's core using `composer require` command only.

#### Related packages
- https://github.com/compwright/codeigniter-installers
- https://github.com/kenjis/codeigniter-composer-installer
- https://github.com/rogeriopradoj/codeigniter-composer

### Simplify unit testing

For me, unit testing is painful in CodeIgniter. Together with [Spark Plug](https://github.com/rougin/spark-plug), you can easily create CodeIgniter instances in your test cases.

## Change Log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/rougin/codeigniter.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/rougin/codeigniter.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/rougin/codeigniter
[link-downloads]: https://packagist.org/packages/rougin/codeigniter
[link-author]: https://github.com/rougin
[link-contributors]: ../../contributors
