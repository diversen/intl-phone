# intl-phone
 
Get intl dial code info from country code

Install:

    composer require diversen/intl-phone

Usage: 

~~~
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
