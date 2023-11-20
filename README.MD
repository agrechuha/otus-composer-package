# Процессор строк

Краткое описание пакета

## Требования

- PHP 8.2

## Установка

```bash
$ composer require agrechuha/otus-composer-package
```

## Использование

```php
<?php
$processor = new StringProcessor()
echo $peocessor->getLength('my string'); // 9
```