# 🔧 Under Development 🔨

# Simple Todo List Application

A simple TODO list web application built with Spring Boot and Kotlin.

## Features

- Add new tasks with descriptions
- View the list of all tasks
- Mark tasks as complete/incomplete
- Edit task descriptions
- Delete tasks

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Java 17** or later installed
- **Gradle** (or **Maven**, depending on your build tool preference)
- **Kotlin 1.8** or later
- **Spring Boot 3.x.x**

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/KendallRey/Sprint-Kotlin-Maven.git
   ```

2. Navigate to the project directory:

  ```bash
  cd simple-todo-list
  ```

3. Build the project:

  ```bash
  ./gradlew build
  ```
  or using Maven:
  ```bash
  mvn clean install
  ```

4. Run the application:

  ```bash
  ./gradlew bootRun
  ```
  or using Maven:
  ```bash
  mvn spring-boot:run
  ```

## Usage
Once the application is running, you can access it at http://localhost:8080. You can use tools like Postman or curl to interact with the API.

API Endpoints
Here are the main API endpoints for interacting with the TODO list:

- GET `/tasks` — Get all tasks
- GET `/tasks/{id}` — Get a specific task by ID
- POST `/tasks` — Create a new task (requires JSON body with description)
- PUT `/tasks/{id}` — Update an existing task (requires JSON body with updated description)
- DELETE `/tasks/{id}` — Delete a task by ID

## Running Tests
```bash
./gradlew test
```
or for Maven:
```bash
mvn test
```