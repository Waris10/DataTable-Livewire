# Laravel Livewire Datatable

This is a **Datatable** built using **Laravel** and **Livewire**. It is designed to display data efficiently with features such as search, pagination, and sorting on each column. The table works with seeded data values for testing and demo purposes.

## Features

- **Search Functionality**: Easily search through the data using the search bar.
- **Pagination with Per-Page Functionality**: Customize how many rows are displayed per page.
- **Sorting**: Sort data in ascending or descending order by clicking on the column headers.
- **Seeded Values**: The table is pre-populated with seeded data for demonstration.

## Screenshot
### Datatable Overview
![Screenshot 2024-10-23 132737](https://github.com/user-attachments/assets/c20c1acb-d2bf-45b9-b0fb-74e1984df714)

## Requirements

- PHP 8.x or later
- Composer
- Node.js and NPM
- Laravel 11.x or later
- Livewire 3.x or later
- MySQL (or any other database supported by Laravel)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Waris10/DataTable-Livewire.git
   cd laravel-livewire-datatable
   ```

2. Install the dependencies:

   ```bash
   composer install
   npm install
   ```

3. Set up your environment file by copying the `.env.example` file:

   ```bash
   cp .env.example .env
   ```

4. Generate the application key:

   ```bash
   php artisan key:generate
   ```

5. Configure your database credentials in the `.env` file:

   ```env
   DB_DATABASE=your_database_name
   DB_USERNAME=your_database_user
   DB_PASSWORD=your_database_password
   ```

6. Run the migrations and seed the database with demo data:

   ```bash
   php artisan migrate --seed
   ```

7. Start the development server:

   ```bash
   php artisan serve
   ```

8. Run the Livewire assets:

   ```bash
   npm run dev
   ```

## Usage

Once the application is up and running, you can access the Datatable by navigating to the appropriate route in your browser.

- Use the **search bar** to filter data by keyword.
- Use the **pagination controls** to view more rows and adjust the number of rows per page.
- Click on any **column header** to sort the data in ascending or descending order.
