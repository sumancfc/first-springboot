# Todo REST API with Spring Boot

This project is a simple RESTful API for managing todos. It's built with Java, Spring Boot, and uses an in-memory H2 database, making it an excellent starting point for beginners learning how to create APIs.

## 🚀 Features

* **Create** a new todo item.
* **Read** all todo items or a single item by its ID.
* **Update** an existing todo item.
* **Delete** a todo item.

## 🛠️ Technologies Used

* **Java 17+**: The core programming language.
* **Spring Boot**: The framework used to build the application.
* **Spring Web**: For creating RESTful endpoints.
* **Spring Data JPA**: For data persistence and database interaction.
* **H2 Database**: An in-memory database used for development and testing.

## ⚙️ How to Run the Application

1.  **Clone the Repository:**
    ```bash
    git clone first-springboot
    cd first-springboot
    ```

2.  **Build the Project:**
    Use your build tool to compile and package the application.
    * **Maven:**
        ```bash
        mvn clean install
        ```

3.  **Run the Application:**
    You can run the application directly from your IDE (e.g., IntelliJ IDEA) or from the command line.
    * **Maven:**
        ```bash
        mvn spring-boot:run
        ```

    The application will start on port `8080` by default.

## 📋 API Endpoints

You can use a tool like **Postman** or **cURL** to interact with the API endpoints. The base URL is `http://localhost:8080/api/todos`.

### GET /api/todos

Retrieves all todo items.

**Example Response:**
```json
[
  {
    "id": 1,
    "title": "Learn Spring Boot",
    "description": "Master the basics of REST APIs",
    "completed": false
  }
]