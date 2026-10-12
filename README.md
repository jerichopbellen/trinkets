# Trinkets

A jewelry e-commerce application developed for a university Web Development project. It features product browsing, search and filtering, shopping cart and checkout workflows, customer accounts, and order management.

## Tech Stack

- Laravel (PHP)
- MySQL
- Blade, JavaScript, CSS

## Setup

1. Install PHP, Composer, Node.js, npm, and MySQL.
2. Clone or download this repository and open a terminal in the project directory.
3. Install the dependencies:

   ```bash
   composer install
   npm install
   ```

4. Copy `.env.example` to `.env` and configure the database connection.
5. Create the database, then generate the application key and run the migrations:

   ```bash
   php artisan key:generate
   php artisan migrate
   ```

6. Build the frontend assets and start Laravel:

   ```bash
   npm run build
   php artisan serve
   ```

7. Open the local URL displayed by Laravel in your browser.

**Note:** Create the MySQL database specified in your `.env` file before running the migrations. If the application requires sample products or other initial data, run the appropriate database seeders.

## Academic Context

- **Year and Term:** 2nd Year - 2nd Term
- **Course:** Web Development
