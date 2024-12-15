# Library Management API

This project is a Flask-based RESTful API for managing a library system. It provides endpoints for CRUD operations on books and includes Swagger UI for interactive API documentation.

---

## Features

- **Add a Book**: Create a new book with title and author.
- **Retrieve a Book**: Get details of a book by its ID.
- **Update a Book**: Modify the title and/or author of an existing book by its ID.
- **Delete a Book**: Remove a book by its ID.
- **List All Books**: Retrieve a list of all books in the library.
- **Swagger UI**: Interactive API documentation available at `/api-docs`.

---

## Requirements

- Python 3.7 or higher
- Flask
- Flask-Swagger-UI

---

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure `swagger.json` exists in the root directory for Swagger UI.

---

## Running the Application

1. Start the Flask server:
    ```bash
    python app.py
    ```

2. Access the API Swagger UI documentation at:
    ```
    http://localhost:3000/api-docs
    ```

---
