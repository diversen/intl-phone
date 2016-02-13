# intl-phone
 
Get intl dial code info from country code (ISO 3166-1 alpha-2 code)
See: [https://en.wikipedia.org/wiki/ISO_3166-1](https://en.wikipedia.org/wiki/ISO_3166-1)

Install:

    composer require diversen/intl-phone

Usage: 

~~~.php
include_once "vendor/autoload.php";

use \diversen\intl\phone;

$p = new phone();
$ary = $p->getCountryInformation('dk');

print_r($ary);
~~~

Yields: 


    Array
    (
        [country_name] => DENMARK
        [dial_code] => 45
    )
