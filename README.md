web site for make users and give them permissionsand roles, you can make books ,categories,publisher and author and user can borrows them from date to date .
`
cd Ahmed-ahmed
```
```
copy .env.example .env
```
```
composer install
```
```
php artisan storage:link
```
```
php artisan key:generate
```
```
php artisan migrate:fresh --seed
```
```
php artisan serve
```
```
username : admin
email : admin@gmail.com
password : admin
