# CakePHP TinyAuth Plugin

[![Build Status](https://api.travis-ci.org/dereuromark/cakephp-tinyauth.png?branch=master)](https://travis-ci.org/dereuromark/cakephp-tinyauth)
[![Latest Stable Version](https://poser.pugx.org/dereuromark/cakephp-tinyauth/v/stable.png)](https://packagist.org/packages/dereuromark/cakephp-tinyauth)
[![Coverage Status](https://coveralls.io/repos/dereuromark/cakephp-tinyauth/badge.png)](https://coveralls.io/r/dereuromark/cakephp-tinyauth)
[![Minimum PHP Version](http://img.shields.io/badge/php-%3E%3D%205.4-8892BF.svg)](https://php.net/)
[![License](https://poser.pugx.org/dereuromark/cakephp-tinyauth/license.png)](https://packagist.org/packages/dereuromark/cakephp-tinyauth)
[![Total Downloads](https://poser.pugx.org/dereuromark/cakephp-tinyauth/d/total.png)](https://packagist.org/packages/dereuromark/cakephp-tinyauth)
[![Coding Standards](https://img.shields.io/badge/cs-PSR--2--R-yellow.svg)](https://github.com/php-fig-rectified/fig-rectified-standards)

A CakePHP 3.x Plugin to handle user authorization the easy way.
This plugin requires PHP5.4+

Please note: This plugin is currently still beta and should only be used with caution. A release will be made once CakePHP 3.0 is stable.

## How to include
Installing the Plugin is pretty much as with every other CakePHP Plugin.

```
"require": {
	"dereuromark/cakephp-tinyauth": "dev-master"
}
```

Then load the plugin:

```php
Plugin::load('TinyAuth', array('bootstrap' => true));
```

For `Plugin::loadAll()` it's

```php
Plugin::loadAll(array(
		'TinyAuth' => array('bootstrap' => true)
));
```

That's it. It should be up and running.

## Docs
See [Docs](/docs).

## Disclaimer
Use at your own risk. Please provide any fixes or enhancements via issue or better pull request.
Some classes are still from 1.2 (and are merely upgraded to 2.x) and might still need some serious refactoring.
If you are able to help on that one, that would be awesome.

### Branching strategy
The master branch is the currently active and maintained one and works with the current 3.x stable version.
Please see the original [Tools plugin](https://github.com/dereuromark/cakephp-tools) if you need TinyAuth for CakePHP 2.x versions.
