# Library-Management-

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)


## Project Overview
The **Library Management System** is a web application designed to help libraries manage their resources efficiently. It provides features to manage books, users, and borrow/return activities while ensuring a seamless user experience.

## Features
- **Book Management**: Add, update, delete  books.
- **Borrow and Return**: Track borrowed books with due dates.

## Tech Stack
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Other Tools**: Postman for API testing

## Installation

### Prerequisites
- Node.js installed on your system
- MySQL installed and running

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd library-management-system
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up the `.env` file:
   Create a `.env` file in the root directory and configure the following variables:
   ```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=your_password
   DB_NAME=library_db
   ```

5. Initialize the database:
   Import the provided SQL file (`database.sql`) into your MySQL server to create the necessary tables.

6. Start the server:
   ```bash
   npm start
   ```

7. Access the application:
   Open your browser and navigate to `http://localhost:3000`.






