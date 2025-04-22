# Shopreviews.com Hyvä Integration for Magento® 2

Hyvä Themes Compatibility Module for the [Shopreviews.com Magento® 2 extension](https://github.com/shopreviews-com/magento2).

This module ensures compatibility between the Shopreviews.com extension and [Hyvä Themes](https://hyva.io/), enabling seamless integration of review displays in Hyvä-powered frontends.

---

## Requirements

- Magento® 2.4.x  
- Hyvä Themes  
- [Shopreviews.com Magento® 2 extension](https://github.com/shopreviews-com/magento2)  
- `hyva-themes/magento2-compat-module-fallback`

---

## Installation

Ensure you have installed the main Shopreviews.com Magento® 2 extension before proceeding.

### Install via Composer

1. Navigate to your Magento® 2 root directory.

2. Require the Hyvä compatibility module via Composer:

   ```bash
   composer require shopreviews-com/magento2-hyva
   ```

3. Enable the module and update Magento:

   ```bash
   php bin/magento module:enable Shopreviews_HyvaConnect
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   ```

4. If Magento® is running in production mode, deploy static content:

   ```bash
   php bin/magento setup:static-content:deploy
   ```

---

## Compatibility

This module ensures compatibility with:

- ✅ Hyvä Themes (via `hyva-themes/magento2-compat-module-fallback`)
- ✅ Shopreviews.com Magento® 2 plugin
- ✅ All supported review platforms listed in the main Shopreviews.com module

---

## License

This project is licensed under:

- [OSL-3.0](https://opensource.org/licenses/OSL-3.0)
- [AFL-3.0](https://opensource.org/licenses/AFL-3.0)

---
