# Job Board API

## Description

This project is an API developed with **Laravel** and **PHP** to manage job postings. It was created as part of an academic assignment, focusing on implementing the back-end (API/server). The project allows a front-end, to consume the data and perform operations related to job postings.

## Features

- Create, read, update, and delete job postings (CRUD).
- Create, update and delete Users.
- Integration with a **MySQL** database for data storage.
- Support for user authentication to secure operations.

## Technologies Used

- **Laravel**: PHP framework used to create the API.
- **PHP**: Programming language for server-side development.
- **MySQL**: Relational database.

## Requirements

- PHP 8.0 or higher.
- Composer.
- MySQL.
- Laravel (compatible version with the project).

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```

3. Install dependencies with Composer:
   ```bash
   composer install
   ```

4. Configure the `.env` file with your database credentials:
   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=database_name
   DB_USERNAME=username
   DB_PASSWORD=password
   ```

5. Run migrations to create database tables:
   ```bash
   php artisan migrate
   ```

6. Start the development server:
   ```bash
   php artisan serve
   ```

7. Access the API at [http://localhost:8000](http://localhost:8000).
## License

This project is licensed under the [MIT License](LICENSE).

