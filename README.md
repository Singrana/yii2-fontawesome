yii2-fontawesome
=========

Yii2 font Awesome assets

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist singrana/fontAwesome "*"
```

or add

```
"singrana/fontAwesome": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Add or modify your asset bundle


```php
	public $depends =
	[
		'singrana\fontAwesome\FontAwesomeAsset'
	];
```