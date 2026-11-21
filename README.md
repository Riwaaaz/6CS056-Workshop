# Training Institute Management System

6CS056 workshop project built with Laravel.

## Features (Workshop 1)

- Student CRUD: create, list, view, edit and delete students
- Course CRUD: create, list, view, edit and delete courses
- Form validation and MySQL storage

## Run locally

```
composer install
npm install && npm run build
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```
