# Unbxd Site Search Module For Magento 2

The Magento 2 module, which provides the ability to search the site using the Unbxd service

Support Magento 2.2.\* || 2.3.\* || 2.4.\*

# Installation Guide

### Install by composer

```
composer require unbxd/magento2-search
php bin/magento module:enable Unbxd_ProductFeed
php bin/magento module:enable Unbxd_SearchJs
php bin/magento module:enable Unbxd_Search
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:flush
```

### Manual installation

1. Download module Unbxd_ProductFeed [Link](https://github.com/unbxd/Magento-2-Extension/archive/1.0.76.zip)
1. Download module Unbxd_SearchJs [Link](https://github.com/unbxd/Magento-2-Search/archive/1.0.12.zip)
2. Download this module [Link](https://github.com/unbxd/Magento-Search-Module/archive/1.0.9.zip)
3. Unzip modules in the folders:

    app\code\Unbxd\ProductFeed  
    app\code\Unbxd\SearchJs  
    app\code\Unbxd\Search

4. Access the root of you Magento 2 instance from command line and run the following commands:

```
php bin/magento module:enable Unbxd_ProductFeed
php bin/magento module:enable Unbxd_SearchJs
php bin/magento module:enable Unbxd_Search
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:flush
```

5. Configure module in backend


 

