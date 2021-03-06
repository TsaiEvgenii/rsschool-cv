![Tsai Eugene CV photo](./images/Tsai_Eugene_150.jpg)
*Tsai Eugene*

***
## Contacts
phone: +375(44)7009019

email: tsai.evgenii@gmail.com

[Linkedin](https://www.linkedin.com/in/yauhen-tsai-55b0691a1/)

***
## About myself
I have worked as a PHP developer (Magento) last 4 years. Before it, I worked as an engineer for more than 8 years I like to find some new ways to study and structure my current knowledge. 

***
## Skills
PHP MySQL, Magento, JQuery, knockout, underscore

***
## Samples of code
```javascript
function factorial(n) {
  if (n < 0 || n > 12)
    throw new RangeError();
  return n <= 1 ? 1 : n * factorial(n - 1);
}
```
```php
$params = $_SERVER;
$params[Bootstrap::INIT_PARAM_FILESYSTEM_DIR_PATHS] = array_replace_recursive(
    $params[Bootstrap::INIT_PARAM_FILESYSTEM_DIR_PATHS] ?? [],
    [
        DirectoryList::PUB => [DirectoryList::URL_PATH => ''],
        DirectoryList::MEDIA => [DirectoryList::URL_PATH => 'media'],
        DirectoryList::STATIC_VIEW => [DirectoryList::URL_PATH => 'static'],
        DirectoryList::UPLOAD => [DirectoryList::URL_PATH => 'media/upload'],
    ]
);
$bootstrap = \Magento\Framework\App\Bootstrap::create(BP, $params);
/** @var \Magento\Framework\App\Http $app */
$app = $bootstrap->createApplication(\Magento\Framework\App\Http::class);
$bootstrap->run($app);
```
```xml
<?xml version="1.0"?>
<theme xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="urn:magento:framework:Config/etc/theme.xsd">
    <title>Tsai Luma</title>
    <parent>Magento/luma</parent>
</theme>
```

***
## Education
SUKHOI STATE TECHNICAL UNIVERSITY OF GOMEL, 2012, Mechanical Engineering

***
##### Certificates:

[Zend Certified Engineer](https://www.zend-zce.com/en/yellow-pages/ZEND031806)

[M2 Professional Developer](https://www.youracclaim.com/badges/572bf903-1ef2-42c1-a878-eab79329607c?source=linked_in_profile)

[M2 JavaScript Developer](https://www.youracclaim.com/badges/1892b4ed-bd68-4949-ab96-326faeb9c84e?source=linked_in_profile)

***
## English
Intermediate

