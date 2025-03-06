# LibraryManagementApplication

A Library Management System built with **Spring Boot** to manage books, users, and transactions efficiently.

## Features
- Book management (add, update, delete, search)
- User management
- Borrowing and returning books
- RESTful API endpoints

## Tech Stack
- **Java 17**
- **Spring Boot 3.4.1**
- **Spring Data JPA**
- **PostgreSQL**
- **Maven**

## Installation

1. **Clone the repository**  
   ```sh
   git clone https://github.com/yourusername/LibraryManagementApplication.git
   cd LibraryManagementApplication
2.**Configure the database**
Update application.properties with your PostgreSQL settings.

3.Build and run the application
./mvnw spring-boot:run

API Endpoints
GET /books - Retrieve all books
POST /books - Add a new book
PUT /books/{id} - Update book details
DELETE /books/{id} - Remove a book

License
This project is licensed under the MIT License.

Author
MuniKrishna

yaml
Copy
Edit
