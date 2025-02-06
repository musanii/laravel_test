## Task Management Application
## Overview

This is a simple Laravel-based Task Management application that allows users to:

- Create, edit, and delete tasks.

- Drag and drop tasks to reorder them, automatically updating priority.

- Save tasks in a MySQL database.



## Features

1. Task creation with name, priority, and timestamps.

2. Task editing and deletion.

3. Drag-and-drop reordering with automatic priority updates.

4. MySQL database integration for task persistence.
   
## Requirements

Before setting up the project, ensure you have the following installed:
1. PHP 8.1+

2. Composer

3. MySQL / LAMPP/ XAMPP

4. Node.js & npm

5. Laravel 8+

## Installation & Setup

1. Ensure your server is up and running
2. Download the zip file and extract it to your preffered location
3. Open your preffered terminal e.g git bash and then into the extracted folder e.g  cd task-manager
4. Install dependencies
   -composer install
   -npm install && npm run dev
5. Environment setup: Copy the example environment file and configure your database connection:
   - cp .env.example .env
   - create a database using your preffered name
   - Update the .env file with your database credentials:
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=task_manager
    DB_USERNAME=root
    DB_PASSWORD=yourpassword
6. Generate application key
   - php artisan key:generate
7. Run migrations and seed the database
   -php artisan migrate --seed
8. Serve the application
   - php artisan serve
    * The application will be accessible at http://127.0.0.1:8000/.


## Usage

 - Navigate to the application in your browser.

- Create tasks with a name and priority.

- Drag and drop tasks to change their order; priority updates automatically.



## Deployment

For production deployment:

1. Set up a web server (e.g., Nginx or Apache).

2. Configure the environment variables in .env.

3. Run database migrations.


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Author
Developed by **Kevin Musanii**.
