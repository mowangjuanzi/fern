# Fern

[English](README.md) | [简体中文](README.zh-CN.md)

PHP 协程 Web 框架。单线程事件循环驱动 `Fiber` 协程，所有网络 I/O 走非阻塞
Stream，并发请求之间互不等待。

## 环境要求

- PHP >= 8.5（CLI）
- Composer 2

## 安装

```bash
git clone git@github.com:mowangjuanzi/fern.git
cd fern
composer install
```

## 自动加载

PSR-4 映射：`Fern\` → `src/`。

```php
<?php

declare(strict_types=1);

require __DIR__ . '/vendor/autoload.php';
```

## 许可证

MIT