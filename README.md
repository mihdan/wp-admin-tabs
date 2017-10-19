# WP Admin Tabs

[![Latest Stable Version](https://poser.pugx.org/typisttech/wp-admin-tabs/v/stable)](https://packagist.org/packages/typisttech/wp-admin-tabs)
[![Total Downloads](https://poser.pugx.org/typisttech/wp-admin-tabs/downloads)](https://packagist.org/packages/typisttech/wp-admin-tabs)
[![Build Status](https://travis-ci.org/TypistTech/wp-admin-tabs.svg?branch=master)](https://travis-ci.org/TypistTech/wp-admin-tabs)
[![codecov](https://codecov.io/gh/TypistTech/wp-admin-tabs/branch/master/graph/badge.svg)](https://codecov.io/gh/TypistTech/wp-admin-tabs)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/TypistTech/wp-admin-tabs/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/TypistTech/wp-admin-tabs/?branch=master)
[![PHP Versions Tested](http://php-eye.com/badge/typisttech/wp-admin-tabs/tested.svg)](https://travis-ci.org/TypistTech/wp-admin-tabs)
[![StyleCI](https://styleci.io/repos/107187828/shield?branch=master)](https://styleci.io/repos/107187828)
[![Dependency Status](https://gemnasium.com/badges/github.com/TypistTech/wp-admin-tabs.svg)](https://gemnasium.com/github.com/TypistTech/wp-admin-tabs)
[![License](https://poser.pugx.org/typisttech/wp-admin-tabs/license)](https://packagist.org/packages/typisttech/wp-admin-tabs)
[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.typist.tech/donate/wp-admin-tabs/)
[![Hire Typist Tech](https://img.shields.io/badge/Hire-Typist%20Tech-ff69b4.svg)](https://www.typist.tech/contact/)

Create tabbed navigation for WordPress admin dashboard, the OOP way.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [The Goals, or What This Package Does?](#the-goals-or-what-this-package-does)
- [Install](#install)
- [Usage](#usage)
  - [Example](#example)
- [Frequently Asked Questions](#frequently-asked-questions)
  - [Can two different plugins use this package at the same time?](#can-two-different-plugins-use-this-package-at-the-same-time)
  - [Do you have real life examples that use this package?](#do-you-have-real-life-examples-that-use-this-package)
- [Support!](#support)
  - [Donate via PayPal *](#donate-via-paypal-)
  - [Why don't you hire me?](#why-dont-you-hire-me)
  - [Want to help in other way? Want to be a sponsor?](#want-to-help-in-other-way-want-to-be-a-sponsor)
- [Developing](#developing)
- [Running the Tests](#running-the-tests)
- [Feedback](#feedback)
- [Change log](#change-log)
- [Security](#security)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## The Goals, or What This Package Does?

## Install

Installation should be done via composer, details of how to install composer can be found at [https://getcomposer.org/](https://getcomposer.org/).

``` bash
$ composer require typisttech/wp-admin-tabs
```

You should put all `WP Admin Tabs` classes under your own namespace to avoid class name conflicts.

- [imposter-plugin](https://github.com/Typisttech/imposter-plugin)
- [mozart](https://github.com/coenjacobs/mozart)

## Usage

### Example

## Frequently Asked Questions

### Can two different plugins use this package at the same time?

Yes, if put all `WP Admin Tabs` classes under your own namespace to avoid class name conflicts.

- [imposter-plugin](https://github.com/Typisttech/imposter-plugin)
- [mozart](https://github.com/coenjacobs/mozart)

### Do you have real life examples that use this package?

Here you go:

 * [Sunny](https://github.com/Typisttech/sunny)
 * [WP Cloudflare Guard](https://github.com/TypistTech/wp-cloudflare-guard)
 * [WP Better Settings](https://github.com/TypistTech/wp-better-settings)
 
*Add your own plugin [here](https://github.com/TypistTech/wp-admin-tabs/edit/master/README.md)*

## Support!

### Donate via PayPal [![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.typist.tech/donate/wp-admin-tabs/)

Love WP Admin Tabs? Help me maintain WP Admin Tabs, a [donation here](https://www.typist.tech/donate/wp-admin-tabs/) can help with it.

### Why don't you hire me?
Ready to take freelance WordPress jobs. Contact me via the contact form [here](https://www.typist.tech/contact/) or, via email info@typist.tech

### Want to help in other way? Want to be a sponsor?
Contact: [Tang Rufus](mailto:tangrufus@gmail.com)

## Developing

To setup a developer workable version you should run these commands:

```bash
$ composer create-project --keep-vcs --no-install typisttech/wp-admin-tabs:dev-master
$ cd wp-admin-tabs
$ composer install
```

## Running the Tests

[WP Admin Tabs](https://github.com/TypistTech/wp-admin-tabs) run tests on [Codeception](http://codeception.com/) and relies [wp-browser](https://github.com/lucatume/wp-browser) to provide WordPress integration.
Before testing, you have to install WordPress locally and add a [codeception.yml](http://codeception.com/docs/reference/Configuration) file.
See [*.suite.example.yml](./tests/) for [Local by Flywheel](https://share.getf.ly/v20q1y) configuration examples.

Actually run the tests:

``` bash
$ composer test
```

We also test all PHP files against [PSR-2: Coding Style Guide](http://www.php-fig.org/psr/psr-2/) and part of the [WordPress coding standard](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards).

Check the code style with ``$ composer check-style`` and fix it with ``$ composer fix-style``.

## Feedback

**Please provide feedback!** We want to make this package useful in as many projects as possible.
Please submit an [issue](https://github.com/TypistTech/wp-admin-tabs/issues/new) and point out what you do and don't like, or fork the project and make suggestions.
**No issue is too small.**

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Security

If you discover any security related issues, please email wp-admin-tabs@typist.tech instead of using the issue tracker.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) and [CODE_OF_CONDUCT](./CODE_OF_CONDUCT.md) for details.

## Credits

[WP Admin Tabs](https://github.com/TypistTech/wp-admin-tabs) is a [Typist Tech](https://www.typist.tech) project and maintained by [Tang Rufus](https://twitter.com/Tangrufus), freelance developer for [hire](https://www.typist.tech/contact/).

Full list of contributors can be found [here](https://github.com/TypistTech/wp-admin-tabs/graphs/contributors).

## License

[WP Admin Tabs](https://github.com/TypistTech/wp-admin-tabs) is licensed under the GPLv2 (or later) from the [Free Software Foundation](http://www.fsf.org/).
Please see [License File](LICENSE) for more information.