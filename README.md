[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)]
[![Release](https://img.shields.io/github/v/release/seobythebay/magento2-remove-keywords?cacheSeconds=600)]
[![GitHub issues](https://img.shields.io/github/issues-raw/seobythebay/magento2-remove-keywords)]


# RemoveKeywords Magento 2 Module
A lightweight Magento 2 plugin to remove the `<meta name="keywords">` output for cleaner HTML and improved SEO.

## Features
- Suppresses the default `<meta name="keywords">` tag
- Zero dependencies, pure PHP plugin
- Easy install in your `app/code` directory

## Installation
1. Clone or download this repo into `app/code/SEOByTheBay/RemoveKeywords`
2. Run:
   ```bash
   php bin/magento module:enable SEOByTheBay_RemoveKeywords
   php bin/magento setup:upgrade
