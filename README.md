# Vanity

A cosmetics e-commerce application developed for a university Web Development project. It features a product catalog with shade options, shopping cart and checkout workflows, customer accounts, and product reviews.

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
5. Generate the application key and run the migrations:

   ```bash
   php artisan key:generate
   php artisan migrate
   ```

6. Build the frontend assets and start the development server:

   ```bash
   npm run build
   php artisan serve
   ```

7. Open the local URL displayed by Laravel in your browser.

**Note:** The database must be created first. If the project requires seeded data or additional services, configure those according to the project's code.

## Academic Context

- **Year and Term:** 2nd Year - 2nd Term
- **Course:** Web Development
