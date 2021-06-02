# Overdose Magento2 Optimizer

## Installation
Add repo to project in Packagist. Then
```
composer require overdose/module-magento-optimizer:v1.0.0 --no-update  (DISCLAYMER: check version before run this command)
composer update overdose/module-magento-optimizer
```

## Functionality
### Main features
- Optimizer moves all js script in the bottom of page, can be configured via adding controllers and paths (pages) which will not be affected 
- Remove Base Url from pages, can be configured via adding controllers and paths (pages) which will not be affected
- Features can be turned on separately, or work both at the same time

## Configurations:
- For excluding controller: add in the field "{module}_{action}_{name}", for example:"cms_index_index""
- For excluding paths: add in the field for example "/gear/bags.html"
## Additional
![img.png](img.png)

## Support
Magento 2.0 | Magento 2.1 | Magento 2.2 | Magento 2.3 | Magento 2.4
:---: | :---: | :---: | :---: | :---:
? | ? | ? | ok | ok