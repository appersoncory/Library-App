# Library Management System

## Overview

This is a simple Library Management System built using Node.js and Express. The system allows users to manage library data including books, patrons, branches, loans, and genres. The web application utilizes a MySQL database for data storage and retrieval.

## Features

- **Books Management**: Add, update, view, and delete books.
- **Patrons Management**: Add, update, view, and delete patrons.
- **Branches Management**: Add, update, view, and delete library branches.
- **Loans Management**: Create, update, view, and delete loans, and manage loan details.
- **Genres Management**: Add, update, view, and delete genres.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, EJS templating
- **Database**: MySQL
- **Version Control**: Git, GitHub

## Project Structure

- **App.js**: Main application file that sets up routes and middleware.
- **public/**: Contains static files such as CSS and client-side JavaScript.
- **views/**: Contains EJS templates for rendering pages.
- **repositories/**: Contains database interaction logic for each entity (books, patrons, branches, loans, genres).
- **database/**: Contains the database connector and schema.
