Packages-list
=============
Test packages

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist miken912/packageslist "*"
```

or add

```
"miken912/packageslist": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \miken912\packageslist\AutoloadExample::widget(); ?>```