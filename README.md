# laravel-binance
Laravel implementation of the Binance crypto exchange trading API

## Install

#### Install via Composer

```
composer require sabramooz/laravel-binance
```

Utilises autoloading in Laravel 5.5+. For older versions add the following lines to your `config/app.php`

```php
'providers' => [
        ...
        sabramooz\binance\BinanceServiceProvider::class,
        ...
    ],


 'aliases' => [
        ...
        'Binance' => sabramooz\binance\BinanceAPIFacade::class,
    ],
```

## Features

Price tickers, balances, trades
