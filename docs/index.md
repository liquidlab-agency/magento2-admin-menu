# Admin Menu

`liquidlab-agency/magento2-admin-menu` is a lightweight Magento 2 module for admin menu customization. It helps teams add and organize Magento backend menu entries, including links to configuration pages and other back-office destinations, using a simple Magento module structure.

## Features

- Register new menu entries
- Link configurations to system settings or other back-office pages

## Installation

Install the package:

```bash
composer require liquidlab-agency/magento2-admin-menu
```

Enable and deploy the module:

```bash
bin/magento module:enable Liquidlab_AdminMenu
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento cache:flush
```

## Configuration

!!! note
    Detailed configuration documentation is coming soon.

## See also

- GitHub repository: [liquidlab-agency/magento2-admin-menu](https://github.com/liquidlab-agency/magento2-admin-menu)
