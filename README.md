# drupal-core-require-dev
[![Packagist](https://img.shields.io/packagist/v/webflo/drupal-core-require-dev.svg)](https://packagist.org/packages/webflo/drupal-core-require-dev)
 [![Packagist](https://img.shields.io/packagist/dt/webflo/drupal-core-require-dev)](https://packagist.org/packages/webflo/drupal-core-require-dev)

---

To fix to dev dependencies tested on Drupal 8.4.0 add ```"webflo/drupal-core-require-dev": "8.4.0"``` to the ```require-dev``` section of your composer.json and run ```composer update``` from the command line.

In other words: this is a _virtual_ package, that causes you to get exactly the versions of Drupal core's dev dependencies as they are specified in Drupal core's `composer.lock` file.

Using ```composer require --dev``` is problematic on an existing site.
