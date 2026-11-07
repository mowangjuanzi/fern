# Fern

[English](README.md) | [简体中文](README.zh-CN.md)

A coroutine web framework for PHP. A single-threaded event loop drives `Fiber`
coroutines over non-blocking streams, so concurrent requests do not wait on each
other.

## Requirements

- PHP >= 8.5 (CLI)
- Composer 2

## Installation

```bash
git clone git@github.com:mowangjuanzi/fern.git
cd fern
composer install
```

## Autoloading

PSR-4 mapping: `Fern\` → `src/`.

```php
<?php

declare(strict_types=1);

require __DIR__ . '/vendor/autoload.php';
```

## License

MIT