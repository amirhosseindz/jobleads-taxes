# Jobleads Taxes
A software that can be used to calculate statistics about the tax income of a country.

# Requirements
[Same as Laravel 5.8 requirements](https://laravel.com/docs/5.8#installation) + MySQL(newer versions recommended)

For the database you should prepare and create one in MySQL.

# Installation
1. Clone the repository and then change the current directory to `jobleads-taxes`:
```
git clone https://github.com/amirhosseindz/jobleads-taxes
cd jobleads-taxes
```
2. Run `composer install`
3. Copy `.env.example` to `.env` and fill the needed parameters for database connection in it.
4. Run `php artisan key:generate`
5. Run `php artisan migrate`

   If you want to fill the database with dummy data, run `php artisan migrate:fresh --seed` instead. Then you can login to the app using these credentials :
   ```
   username: demo
   password: demo123
   ```
6. Run `php artisan serve` and enjoy!
