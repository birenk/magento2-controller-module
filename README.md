#Magento 2 Controller Module Example

## To install:

Install with Composer!

    composer require birenk/magento2-controller-module:2.0.*

Then you'll need to modify `app/etc/config.php` to activate the module. It should look a little like this:

    <?php
    return array (
        'modules' =>
        array (
            ...
            'Biren_HelloWorld' => 1,
            ),
          );
