# Helpdesk Ticketing Management System for Employees

This repository contains a Helpdesk Ticketing Management System designed for employees to submit and track their support requests. The system is built using Node.js, HTML, CSS, MySQL, and JavaScript.

![Screenshot](screenshot.png)

## Features

- Employees can create new support tickets for their issues.
- Real-time status updates for tickets (Open, In Progress, Resolved, Closed).
- User-friendly web interface built with HTML and CSS.
- Backend powered by Node.js and MySQL database.
- Interactive and responsive design for seamless user experience.

## Prerequisites

- Node.js and npm installed on your machine.
- MySQL database set up with the required schema.

## Installation

Clone the repository:

    git clone https://github.com/your-username/helpdesk-ticketing-system.git

Navigate to the project directory:

    cd helpdesk-ticketing-system

Install the dependencies:

    npm install

Configure the database:

Create a MySQL database with the required schema (details can be found in database_schema.sql).
Configure environment variables:

Rename .env.example to .env and provide your database connection details.

Usage
Start the application:

    npm start

Open your web browser and navigate to http://localhost:3000.

Employees can create new tickets, view their existing tickets, and track their status.

Admins can log in to manage and resolve tickets.

Folder Structure

public/: Contains static assets such as CSS stylesheets and client-side JavaScript files.

views/: Contains HTML templates for rendering pages.

routes/: Contains route handlers for different endpoints.

models/: Contains data models for interacting with the database.

controllers/: Contains logic to handle business operations.

config/: Contains configuration files, including database connection setup.

app.js: Entry point of the application.

### Acknowledgments

This system was developed using various technologies and libraries. We would like to acknowledge the open-source communities behind Node.js, MySQL, and other tools.

### License

This project is licensed under the MIT License.
