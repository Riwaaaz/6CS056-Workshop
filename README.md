# Training Institute Management System

6CS056 workshop project built with Laravel.

## Features (Workshop 1)

- Student CRUD: create, list, view, edit and delete students
- Course CRUD: create, list, view, edit and delete courses
- Form validation and MySQL storage

## Workshop 2: MVC refactor

- StudentController and CourseController with resource routes
- Named routes and route model binding
- Shared layout with navbar and footer (Blade components)
- Reusable components for alerts, form fields and delete buttons
- One shared form for create and edit

## Run locally

```
composer install
npm install && npm run build
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```
