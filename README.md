# Laravel REST API Sample

Laravel 9.x REST API example with Product resource.

> **Recommended GitHub repo name:** `laravel-rest-api`

> **Important:** Laravel 9 reached end-of-life. For new projects use Laravel 11 or 12.

## API Endpoints

| Method      | Endpoint                 | Description          |
|-------------|--------------------------|----------------------|
| GET         | `/api/v1/product`        | List products        |
| POST        | `/api/v1/product`        | Create product       |
| GET         | `/api/v1/product/{id}`   | Show product         |
| PUT/PATCH   | `/api/v1/product/{id}`   | Update product       |
| DELETE      | `/api/v1/product/{id}`   | Delete product       |

## Requirements

- PHP 8.0.2+
- Composer
- Laravel 9.x

## Installation

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

## License

MIT
