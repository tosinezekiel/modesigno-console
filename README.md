# Modesign
This application is aimed at taking digital clothing to the next level, maintaining luxury and interest of all tech enthusiast.

# Requirements
```sh
    "php": "^8.0"
```
# Setting it up
These are the steps to get the app up and running. Once you're using the app.

1. Clone the repository
2. `composer install`
3. Rename `.env.example` to `.env` and run `php artisan key:generate`
4. Create a MySQL database. Add the database name to your `.env`
5. Run migrations: `php artisan migrate --seed`
6. Run `php artisan test`
