<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# ResepSaji Backend

**ResepSaji Backend** is the backend component of the ResepSaji application, designed to manage the data and operations related to home-cooked recipes. This robust backend system serves as the backbone of the application, handling all business logic, data storage, and user management.

## Key Features
- **Role Management**: The backend supports multiple user roles, including:
  - **Admin**: Administrators can manage users, recipes, and categories, ensuring that the content is well-organized and up-to-date.
  - **User Management**: The system provides tools for managing user permissions and roles, making it easy to control access to various features of the application.

- **API Development**: Built with RESTful principles, the backend exposes a well-defined API that allows the frontend to interact seamlessly with the database. This API handles requests for recipes, user authentication, and other operations.

- **Fillament Integration**: Utilizing [Fillament](https://fillamentphp.com/), a modern admin panel for Laravel, the backend provides an elegant and user-friendly interface for administrators to manage the application efficiently. Fillament enhances productivity by offering features such as:
  - Intuitive dashboards
  - Easy CRUD operations for managing resources
  - Real-time updates and notifications

## Technologies Used
- **Backend Framework**: Developed using [Laravel](https://laravel.com/), a powerful PHP framework that provides a clean and elegant syntax while handling the complexity of web application development.
- **Admin Panel**: [Fillament](https://fillamentphp.com/) is employed to create an administrative interface that simplifies resource management and improves user experience.
- **Database**: The backend utilizes a relational database management system (such as MySQL or PostgreSQL) for data storage, ensuring data integrity and efficient querying.

## Project Background
This project was initiated as part of a comprehensive course from BWA, which focused on modern web development practices, particularly in backend development with Laravel. The course emphasized best practices in API design, database management, and user authentication, all of which have been implemented in ResepSaji Backend.

## Installation
To set up the backend locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/username/resepsaji-backend.git
   cd resepsaji-backend
2. Install dependecies:
   ```bash
   composer install
   npm install 
3. Set up the environment configuration by creating the .env file:
   ```bash
   cp .env.example .env
   php artisan key:generate
4. Run database migrations:
   ```bash
   php artisan migrate
5. Start the server:
   ```bash
   php artisan serve

