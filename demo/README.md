# Spring Boot Hello World Demo

I've created this simple Spring Boot application as part of my journey through the Spring Boot Quickstart Guide. The goal was to build a classic "Hello World!" web service that responds to browser requests.

## Table of Contents
1. [Project Description](#project-description)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Running the Application](#running-the-application)
5. [Conclusion](#conclusion)

## Project Description

In this project, I implemented a basic web service that greets users. When you access the endpoint `http://localhost:8080/hello`, the application responds with a friendly message. If a name is provided in the request, it customizes the greeting; if not, it defaults to "World."

## Features

- **Dynamic Greeting**: The service greets users by name if they provide it as a request parameter. For example, navigating to `http://localhost:8080/hello?name=Sifiso` would respond with "Hello Sifiso!".
- **Default Response**: If no name is given, the application defaults to "Hello World!"

## Technologies Used

- **Spring Boot**: This project uses Spring Boot for quick and easy setup of the web service.
- **Java**: The application is built using Java, leveraging its capabilities to handle web requests seamlessly.

## Running the Application

To run the application, navigate to the project directory in your terminal and execute the following command:

```bash
./mvnw spring-boot:run
```

Once the application is running, open your browser and go to http://localhost:8080/hello to see the greeting.

## Conclusion

Working through this guide has been a valuable experience in learning how to set up and run a Spring Boot application. I'm excited to continue exploring Spring and applying what I've learned to more complex projects in the future.

