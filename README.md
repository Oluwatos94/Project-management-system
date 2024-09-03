# Project Management System

This is a web application designed to streamline the management of projects and tasks within an organization.

## Features

- **User Authentication & Authorization**: Users can register, log in, and manage their profiles securely.
- **Project Management**: Users can create, update, view, and delete projects.
- **Task Management**: Tasks can be created, updated, viewed, and deleted. Each task can be assigned to specific users.
- **User Dashboard**: A personalized dashboard displays all tasks assigned to a user, along with the total number of tasks.
- **Task Assignment**: Tasks can be assigned to different users, allowing for effective project delegation and tracking.
- **Task Overview**: Users can view all tasks assigned to them for better task management and prioritization.

## Getting Started

To get started with this project, clone the repository and follow the setup instructions below.

## Installation

1. **Clone the repository**: `git clone https://github.com/Oluwatos94/project-management-system.git`
2. **Navigate to the project directory**: `cd project-management-system`
3. **Install dependencies**: `composer install`  and `npm install`.
4. **Set up environment variables**: Copy `.env.example` to `.env` and configure your database and other environment settings.
5. **Run migrations**: `php artisan migrate`
6. **Serve the application**: `php artisan serve`  `npm run dev`

## Usage

Once the application is up and running, you can:

- Register a new user account or log in with existing credentials.
- Create, view, update, and delete projects and tasks.
- Assign tasks to users and monitor task progress through the dashboard.

## License

This project is open-source and available under the [MIT License](LICENSE).
