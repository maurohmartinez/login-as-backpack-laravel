# Login as — Backpack for Laravel
Use a simple url to login with with users having different roles to test your application locally.

<img width="796" alt="Screenshot 2023-11-25 at 14 01 52" src="https://github.com/maurohmartinez/login-as-backpack-laravel/assets/33960976/52a0d444-4827-4dbf-bbea-079b47815045">


## How to install
1. Use composer to require this project **locally**
```shell
composer require maurohmartinez/login-as-backpack-laravel --dev
```

2. Publish the config file
```shell
   php artisan vendor:publish --provider="MHMartinez\LoginAs\app\Providers\LoginAsServiceProvider" --tag=config
```

3. Customize the config file
```php
[
    /**
     * E.g.: for https://my-web.com/admin/login use simply "admin/login"
     */
    'login_path' => 'admin/login',   
]
```

4. [Optional] Publish config views if you need to customize them
```shell
   php artisan vendor:publish --provider="MHMartinez\LoginAs\app\Providers\LoginAsServiceProvider" --tag=view
```

## Contact
Project Link: [https://github.com/maurohmartinez/login-as-backpack-laravel](https://github.com/maurohmartinez/login-as-backpack-laravel)

## Credits
- [Mauro Martinez](https://inspiredpulse.com/) Developer
- [Cristian Tabacitu](https://tabacitu.ro/) For creating [Backpack for Laravel](https://backpackforlaravel.com/)!
