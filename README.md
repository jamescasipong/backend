# Backend API with PHP (Laravel) and MySQL

## Project Overview

This project is a backend API built using PHP (Laravel) and MySQL. It provides endpoints for user authentication, inventory management, and sales tracking.

## Getting Started

To get started, you need to set up the following tools:

1. **PHP**: Make sure PHP is installed on your system.
2. **MySQL**: Install MySQL for database management.
3. **Composer**: This is PHP's dependency manager, similar to npm for JavaScript. For what purposes? Welp, tt is used for managing packages, such as installing useful packages like web-token, qr-code, etc., so you don't have to code them yourself.

After installing these tools, follow this [tutorial](https://www.youtube.com/watch?v=iBaM5LYgyPk) to configure PHP and install Laravel; installing Laravel just sucks and is harder than coding in PHP lmaoo. The video will guide you through the necessary PHP configurations and the installation process for Laravel.

## Project Structure

Here’s a brief overview of the project structure:

- `app/`: Contains the core application code.
  - `Http/Controllers/`: Controller classes handling request logic.
  - `Models/`: Eloquent models for database interactions.
  - `Providers/`: Service providers for application services.
- `config/`: Configuration files for the application.
- `database/`: Database migrations, seeds, and factories.
- `public/`: Publicly accessible files such as `index.php`.
- `resources/`: Views and language files.
- `routes/`: Route definitions for the application.
- `storage/`: Logs, cache, and file storage.
- `tests/`: Unit and feature tests for the application.
- `.env`: Environment variables for configuration.
- `composer.json`: Project metadata and dependencies.
- `artisan`: Laravel command-line interface.

## Dependencies

- **Laravel**: PHP framework for web application development.
- **MySQL**: Database management system.
- **PHP**: Programming language for server-side logic.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   
   or

   Download & install GitHub Desktop, use it to clone it :) 
   
   ```

2. **Install dependencies:**
   ```bash
   composer install
   ```

3. **Set up environment variables:**
   Copy `.env.example` to `.env` and update the environment variables as needed.
   ```bash
   cp .env.example .env
   ```

4. **Generate the application key:**
   ```bash
   php artisan key:generate
   ```

5. **Run migrations and seed the database:**
   ```bash
   php artisan migrate --seed
   ```

6. **Start the development server:**
   ```bash
   php artisan serve
   ```

## Endpoints

- **POST /signin**: Authenticate users.
- **POST /signup**: Register new users.
- **GET /**: Retrieve all users.


<!--## Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.->
