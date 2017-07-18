# LaraArticlesAPI
REST JSON API of users articles. Develped using Laravel 5.5. Tested with according unit and acceptance tests (PhpUnit/Behat).

Setup to get the API up and running. Create the database (and database user if necessary) and add them to the .env file.

DB_DATABASE=db_name
DB_USERNAME=db_user
DB_PASSWORD=db_password

On your command-line type:

$composer install
$ php artisan migrate
$php artisan db:seed
$ php artisan serve

App URL on:
http://localhost:8000

Thanks for your time.
