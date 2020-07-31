## Install project when git clone

- Open the console and cd your project root directory
- Run `cp .env.example .env`
- Run `composer install` or `php composer.phar install`
- Run `php artisan key:generate`
- Run `php artisan migrate`
- Run `php artisan db:seed` to run seeders, if any.
- Run `php artisan serve`

# Process

```
composer require laravel/ui
npm install && npm run dev
```

---

```
php artisan make:model Role -m
```

---

```
<!-- Create Seeder to Test Data -->
php artisan make:seed UsersTableSeeder
php artisan make:seed RolesTableSeeder
```

---

```
php artisan db:seed
```

---

```
php artisan make:controller Admin/DashboardController
php artisan make:controller Author/DashboardController
php artisan make:middleware AdminMiddleware
php artisan make:middleware AuthorMiddleware
```

---

```
php artisan make:model Tag -m
```

```
php artisan make:controller Admin/TagController -r
-r là --resource

php artisan route:list
```

```
composer require brian2694/laravel-toastr
```
