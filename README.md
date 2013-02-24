# PHP Units of Measure
master: [![Build Status](https://travis-ci.org/triplepoint/php-units-of-measure.png?branch=master)](https://travis-ci.org/triplepoint/php-units-of-measure)

## Introduction
This is a PHP library for representing and converting physics units of measure.

## Installation
This library is best included in your projects via composer.  See the [Composer website](http://getcomposer.org/)
for more details, and see the [Packagist.org site for this library](https://packagist.org/packages/triplepoint/php-units-of-measure)

## Use
TODO

## Testing and Development
First, install Composer:

``` bash
cd {path_to_project_root}
php -r "eval('?>'.file_get_contents('https://getcomposer.org/installer'));"
```
For development, install with the dev dependencies:

``` bash
./composer.phar install --verbose --prefer-dist --dev
```

### Continuous Integration
Continuous integration is handled through Travis-CI.
- https://travis-ci.org/triplepoint/php-units-of-measure

### API Documentation
API documentation (such as it is) is handled through GitApiDoc.
- http://gitapidoc.com/api/triplepoint/php-units-of-measure

### Unit Tests
All the tests associated with this project can be manually run with:

``` bash
vendor/bin/phpunit -c ./tests/phpunit.xml.dist ./tests
```

### CodeSniffer
Codesniffer verifies that coding standards are being met.  Once the project is build with development dependencies, you can run the checks with:

``` bash
vendor/bin/phpcs --encoding=utf-8 --extensions=php --standard=./tests/phpcs.xml -nsp ./
```