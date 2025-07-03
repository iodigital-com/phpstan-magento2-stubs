# PHPStan Magento 2 stubfiles

[PHPStan](https://phpstan.org/) stubfiles for the Magento 2 framework. Currently the stub files are targeted towards the 2.4.7.x version.

## Installation

```bash
composer require --dev iodigital-com/phpstan-magento2-stubs
```

If you use the [phpstan/extension-installer](https://github.com/phpstan/extension-installer) package. You do not need any further configuraton. However if you do not use this package. Add the following configuration to your `phpstan.neon` file.

```yaml
includes:
  - ./vendor/iodigital-com/phpstan-magento2-stubs/extension.neon
```

    ## Notes
It is not possible to replace @method in stubFiles since it will overwrite the complete phpdoc. This means you will have to copy all the @methods from that specific class. Please ignore this in your PHPStan Baseline.
