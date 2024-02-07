# User Management System

This is a simple user management system built with Angular for the frontend and Laravel for the backend. It allows users to add, view, and delete contacts.

## Installation

Clone the repository:
```bash
git clone https://github.com/KashifWebDev/contact-management-backend.git
```

Navigate to the frontend directory:
```bash
cd user-management-system/frontend
```

Install dependencies:
```bash
composer install
```


Create a copy of the .env.example file and rename it to .env:
```bash
cp .env.example .env
```


Generate an application key:
```bash
php artisan key:generate
```


Start the Laravel development server:
```bash
php artisan serve
```


Your backend API will be available at http://localhost:8000.



## How It Works
The frontend is built with Angular and provides a user interface to add, view, and delete contacts.
The backend is built with Laravel and serves as the API for user management operations.
Angular components interact with the backend API using HTTP requests (GET, POST, DELETE) to perform CRUD operations on user data.
Changes made in the frontend (e.g., adding or deleting users) trigger corresponding requests to the backend API, which updates the database accordingly.
