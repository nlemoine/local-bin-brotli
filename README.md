# local-bin-brotli

This package provides pre-compiled brotli binaries for seamless local usage on any platform.

## Installation

```bash
composer require n5s/local-bin-brotli
```

## Usage

To get the brotli binary path for the current platform:

```php
use n5s\LocalBin\Brotli;

$brotli = Brotli::getPath();
```