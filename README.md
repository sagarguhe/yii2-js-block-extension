Js Block
========
A simple Js Block extension

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist tinkers/yii2-js-block "*"
```

or add

```
"tinkers/yii2-js-block": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php \tinkers\widgets\JsBlock::begin() ?>
<script>
    $(function(){
        jQuery(".company_introduce").slide({mainCell:".bd ul",effect:"left",autoPlay:true,mouseOverStop:true});
    });
</script>
<?php \tinkers\widgets\JsBlock::end()?>
```