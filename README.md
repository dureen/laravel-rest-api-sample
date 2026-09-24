# Laravel REST API Sample

> **Status: Archived** – Laravel 9 sample from 2022.

Laravel 9.x REST API example with a Product resource using `apiResource`.

## Important Notes

- **Laravel 9 reached End-of-Life.**  
  Do **not** use this project for new development.
- For new projects, start with **Laravel 11** or **Laravel 12**.

## API Endpoints

| Method      | Endpoint                 | Description          |
|-------------|--------------------------|----------------------|
| GET         | `/api/v1/product`        | List products        |
| POST        | `/api/v1/product`        | Create product       |
| GET         | `/api/v1/product/{id}`   | Show product         |
| PUT/PATCH   | `/api/v1/product/{id}`   | Update product       |
| DELETE      | `/api/v1/product/{id}`   | Delete product       |

## Requirements (historical)

- PHP 8.0.2+
- Composer
- Laravel 9.x

## How to Run (for reference only)

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

## License

MIT
