### Setup Steps

1. Clone the repository
2. Copy `.env.example` to `.env`
3. Create database and update DATABASE_NAME in `.env`
4. Run following commands 
```
composer install
npm install
php artisan key:gen
php artisan migrate --seed
php artisan serve 
```

#### Credentials
- email : admin@gmail.com
- passwor : admin
