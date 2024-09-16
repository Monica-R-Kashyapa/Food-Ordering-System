## Food Ordering System
This Food Ordering System is a web application designed for managing food orders, restaurants, and dishes. It includes both a front-end for users and an admin panel for managing various aspects of the system.

## Features
- User registration and login
- Restaurant and dish management
- Order management
- Admin dashboard for managing users, dishes, orders, and restaurants
- Success page for confirming actions

## File Structure
The project contains the following PHP files and components:

- Admin
  - admin/: Contains PHP files for the admin panel to manage dishes, orders, restaurants, and more.

- Database Connection
  db: Includes the database connection scripts for interacting with the MySQL database.
  
- User End
  index.php: The landing page of the food ordering system.
  login.php: User login page.
  logout.php: User logout functionality.
  register.php: User registration page.
  order.php: Page for placing orders.
  restaurant.php: Page displaying restaurant details.
  success.php: Page shown after a successful action.

- Admin End
  manage_dishes.php: Admin page for managing dishes.
  manage_orders.php: Admin page for managing orders.
  manage_restaurants.php: Admin page for managing restaurants.

- Database Schema
  schema.sql: SQL queries for setting up the database schema.

- Styling
  css/: Contains CSS files for styling the application.
  html/: Contains HTML files if needed for templates.

## Usage
- User End:
  Visit index.php to view available restaurants and dishes.
  Use login.php and register.php for user authentication.
  Place orders via order.php.

- Admin End:
  Access the admin panel through the admin/ directory.
  Manage dishes, orders, and restaurants using the respective admin pages.

## Results 
