# `vendor:publish` for Lumen framework

[`laravelista/lumen-vendor-publish`](https://github.com/laravelista/lumen-vendor-publish) is **abandoned**.

This package contains a single command borrowed from the Laravel framework that enables you to use `php artisan vendor:publish` in your Lumen application.

## Overview

This package contains a copy of the class from [`Illuminate/Foundation/Console/VendorPublishCommand`](https://github.com/laravel/framework/blob/9.x/src/Illuminate/Foundation/Console/VendorPublishCommand.php).

**This repository now follows the Lumen framework versioning.** Use the appropriate version of this package for your Lumen application. _eg. Lumen ^9.0 -> LumenVendorPublish ^9.0. etc._

## Installation

```
composer require mazfreelance/lumen-vendor-publish=^9.0
```

## Usage

To be able to use it you have to add it to your `app/Console/Kernel.php` file:

```
protected $commands = [
    \Mazfreelance\LumenVendorPublish\VendorPublishCommand::class
];
```

## Contributing

Thank you for considering contributing to LumenVendorPublish!

## Code of Conduct

In order to ensure that the open-source community is welcoming to all.

## License

LumenVendorPublish is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
