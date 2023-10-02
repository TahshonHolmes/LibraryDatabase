# Personal Home Library Database

![Library Image](LibraryPicture.jpg)

## Overview

This project is a personal home library database designed to help manage and organize your book collection. It includes a SQLite database to store book information and a corresponding website for easy access and interaction.

## Features

- **Database Structure**:
  - The database stores essential book details like title, author, genre, publish date, and more.

- **Website Interface**:
  - Provides a user-friendly interface to view, search, and manage your book collection.

- **Genre-based Searching**:
  - Easily search for books by genre to quickly find what you're looking for.

- **Lending Capabilities**:
  - Allows you to track books that have been borrowed by friends.

- **Additional Features (Optional)**:
  - Book reviews, recommendations, etc.

## Getting Started

### Database Setup

1. **SQLite Installation**:
   - Make sure you have SQLite installed on your system.

2. **Create Database**:
   - Use the following command to create your library database:
     ```
     sqlite3 library.db
     ```

3. **Define Database Structure**:
   - Run the SQL command to define the table structure.

### Import Data

1. **CSV Import**:
   - Use the SQLite command-line interface to import your book data from the CSV file.

   ```sql
   .mode csv
   .import BookCatalogue.csv Books
