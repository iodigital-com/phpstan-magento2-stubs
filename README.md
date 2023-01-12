# PHPStan Magento 2 stubfiles

PHPStan stubfiles for the Magento 2 framework. Currenly the stub files are targeted towards the 2.4.5-p1 version.

## Installation

```bash
composer require --dev melvinversluijs/phpstan-magento2-stubs
```

If you use the [phpstan/extension-installer](https://github.com/phpstan/extension-installer) package. You do not need any further configuraton. However if you do not use this package. Add the following configuration to your `phpstan.neon` file.

```yaml
includes:
  - ./vendor/melvinversluijs/phpstan-magento2-stubfiles/extension.yml
```
