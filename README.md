# Laravel IPTV

Esta é uma biblioteca que controla lista de canais iptv  e gera uma lista m3u

## Instalação

Para instalar você precisa ter laravel 5.4.

### Execute o comando abaixo na raiz do projeto para baixar.

```bash
composer require felipefm32/laravel-iptv
```


### Depois adicione  no arquivo 'config/app.php' 

```php
<?php
...
'providers' => [
...
Felipefm32\LaravelIPTV\IPTVProvider::class,
...
];

```

### Migre o banco de dados

```bash
php artisan migrate
```
