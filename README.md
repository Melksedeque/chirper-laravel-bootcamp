<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Laravel Bootcamp

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you're new to Laravel, feel free to jump into the [Laravel Bootcamp](https://bootcamp.laravel.com). The Laravel Bootcamp will walk you through building your first Laravel application using Eloquent. It's a great way to get a tour of everything that Laravel and Eloquent have to offer.

# Chirps System

The Chirps System is a web application developed using the Laravel framework. It allows users to post short messages similar to tweets, called "Chirps," and interact with Chirps from other users.

## Features

- User registration and authentication.
- Posting, editing, and deleting Chirps.
- Chirp feed, displaying posts from followed users.
- Liking and commenting on Chirps.
- User profiles with a list of Chirps and user information.

## How to Set Up the Project

Follow the instructions below to set up the project locally:

### Requirements

Make sure you have the following requirements installed on your machine:

- PHP 7.4 or higher
- Composer
- Node.js and npm
- SQLite database or another database supported by Laravel

### Step 1: Clone the Repository

Clone this repository to your preferred local directory:

```
git clone https://github.com/Melksedeque/chirper-laravel-bootcamp.git
```

### Step 2: Install Dependencies

Navigate to the project directory and install PHP and JavaScript dependencies:

```
cd chirper-laravel-bootcamp
composer install
npm install
```

### Step 3: Configure the Environment

Create a copy of the `.env.example` file and rename it to `.env`. Then, generate the application key and set up the database information in the `.env` file:

```
cp .env.example .env
php artisan key:generate
```

Configure the database credentials in the `.env` file:

```
DB_CONNECTION=sqlite
DB_DATABASE=/path/to/database.sqlite
```

### Step 4: Create the Database

Create a new SQLite database file by running:

```
touch database/database.sqlite
```

Then, run the migrations to create the necessary tables:

```
php artisan migrate
```

### Step 5: Start the Server

Start the Laravel development server:

```
php artisan serve
```

Access the application at `http://localhost:8000` or `http://127.0.0.1:8000`.

## How to Use the Chirps System

After setting up the project, you can create a user account and start using the Chirps system.

- Register a new account.
- Log in to the application with your credentials.
- Post Chirps on the main page.
- Explore Chirps from other users in your feed.
- Like and comment on Chirps from other users.

## Conclusion

The Chirps System is a simple yet powerful application developed with Laravel. Feel free to explore the source code and customize the system according to your needs. If you have any questions or need assistance, don't hesitate to reach out!

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
