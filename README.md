# PHPFastCGI PPI Adapter

[@ppi]: http://www.ppi.io/ "PPI Framework"

[![Join the chat at https://gitter.im/PHPFastCGI/PPIAdapter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/PHPFastCGI/PPIAdapter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Latest Stable Version](https://poser.pugx.org/phpfastcgi/expressive-adapter/v/stable)](https://packagist.org/packages/phpfastcgi/expressive-adapter)
[![Build Status](https://travis-ci.org/PHPFastCGI/PPIAdapter.svg?branch=v0.5.0)](https://travis-ci.org/PHPFastCGI/PPIAdapter)
[![Coverage Status](https://coveralls.io/repos/PHPFastCGI/PPIAdapter/badge.svg?branch=master&service=github)](https://coveralls.io/github/PHPFastCGI/PPIAdapter?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/PHPFastCGI/PPIAdapter/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/PHPFastCGI/PPIAdapter/?branch=master)
[![License](https://poser.pugx.org/PHPFastCGI/PPIAdapter/license.png)](https://packagist.org/packages/PHPFastCGI/PPIAdapter)

A PHP package which allows [PPI][@ppi] applications to reduce overheads by exposing their Request-Response structure to a FastCGI daemon.

Visit the [project website](http://phpfastcgi.github.io/).

## Introduction

Using this package, [PPI][@ppi] applications can stay alive between HTTP requests whilst operating behind the protection of a FastCGI enabled web server.

## Current Status

This project is currently in early stages of development and not considered stable. Importantly, this library currently lacks support for uploaded files.

Contributions and suggestions are welcome.

## Installing

```sh
$ composer require "phpfastcgi/ppi-adapter:dev-master"
```

## Usage

_Coming soon._