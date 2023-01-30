# Installation guide

```shell
mkdir phpinfo
cd phpinfo

composer require codedigitally/phpinfo

```

Using the Package

```php
require __DIR__ . '/vendor/autoload.php';


use MyPHPInfo\PHPinfo;

$info = new PHPinfo();

var_dump($info->version());
```
