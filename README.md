# Instaframe

It's a metapackage for the [source code repository](https://github.com/swissup/module-instaframe).

#### Installation

```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/instaframe --prefer-source
bin/magento module:enable Swissup_Core Swissup_Instaframe
bin/magento setup:upgrade
```
