# Codeigniter

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]][link-license]
[![Total Downloads][ico-downloads]][link-downloads]

This is the `system` directory of [Codeigniter 3](https://codeigniter.com/userguide3/) prepared as a package in [Composer](https://getcomposer.org/).

## Installation

Install `Codeigniter` via [Composer](https://getcomposer.org/):

``` bash
$ composer require rougin/codeigniter
```

If wanting to create a new project, the [Ignite](https://roug.in/ignite/) package can be used instead:

``` bash
$ composer create-project rougin/ignite "ciacme"
```

## Why?

I was a big fan of `Codeigniter 3` back in the day as it is my very first PHP framework to work with. With this, I tried to create this package to provide quality of development improvements when writing projects under `Codeigniter 3` before and the following other reasons below:

### One-command update

This package provides an easy way to update the internals of `Codeigniter 3`:

``` bash
$ composer update
```

With a simple command, there's no need to perform copy and pasting of files whenever there is an update.

### Out of curiosity

It just gained [my interest](https://roug.in/projects/) before if there is an alternative way to update a `Codeigniter 3` project with minimal effort.

### For unit testing

Together with [Spark Plug](https://roug.in/spark-plug/), this package can easily create `Codeigniter 3` instances in unit tests.

## `Ignite` project

[Ignite](https://roug.in/ignite/) is yet another `Codeigniter 3` project template with a twist. It uses an alternative and secured directory structure for new `Codeigniter 3` projects. Instead of the common `system` directory, this project template uses `rougin/codeigniter` as its base package.

## Changelog

Please see the [Change Log](https://codeigniter.com/userguide3/changelog.html) page from the `Codeigniter 3` website for its latest updates.

## License

The MIT License (MIT). Please see [LICENSE][link-license] for more information.

[ico-version]: https://img.shields.io/packagist/v/rougin/codeigniter.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/rougin/codeigniter.svg?style=flat-square

[link-downloads]: https://packagist.org/packages/rougin/codeigniter
[link-license]: https://github.com/rougin/codeigniter/blob/master/LICENSE.md
[link-packagist]: https://packagist.org/packages/rougin/codeigniter