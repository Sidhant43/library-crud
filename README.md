# library-crud
A lightweight CRUD (Create, Read, Update, Delete) application built with Express.js and MySQL for managing a book library. Enables adding new books, retrieving all books, and includes a database seeding option for mock data. Simple and extensible.
# CRUD Express MySQL App

A simple CRUD application using Express.js and MySQL to manage a library of books.

## Setup

1. Clone the repo.
2. Install dependencies: `npm install`.
3. Set up MySQL: Create a database named `library` and update user/password in `dbConfig` in `getAllBooks.js` and `addNewBook.js`.
4. Run the app: `npm start`.

## Seeding Database

Seed the database with mock data:

```bash
npm run seed
