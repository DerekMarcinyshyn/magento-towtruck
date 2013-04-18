#Magento Tow Truck

##Description

A Magento module to call the [Mozilla Tow Truck](http://towtruck.mozillalabs.com/) in the Admin section to make collaboration with Magento Administators surprisingly easy.

##Install

Add the 3 files to your Magento website. Currently, there is one core file edit that involves copy and pasting this line of code at the bottom of

```php
/app/design/adminhtml/default/default/template/page/head.phtml
```

```php
<?php echo $this->getChildHtml('mozilla.towtruck'); ?>
``` 

##To do

Add composer or modman installation methods or upload to Magento Connect. 

##Tested

Currently only tested on Magento Enterprise Edition 1.12.0.2 but should work for any Magento version.