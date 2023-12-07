# TP-MICROSERVICES Repository

## Overview

This repository hosts a microservices architecture featuring key components such as an Eureka Server, a Gateway, and two distinct services: "Car Service" and "Client Service." The central objective of these services is to establish seamless communication among themselves. Specifically, the "Car Service" oversees interactions with a MySQL database that stores data related to cars, while the "Client Service" is responsible for similar interactions, managing data associated with clients in another MySQL database. The Eureka Server assumes a pivotal role in the ecosystem, overseeing service registration and discovery processes.

## Technologies Used

- **Spring Tool Suite**: Integrated development environment for Spring Boot applications.
- **Java (Spring Boot)**: Framework for building Java-based microservices.
- **MySQL**: Relational database management system.

## Project Structure

1. **Eureka Server:** Manages service registration and discovery.
2. **Gateway:** Serves as an entry point for accessing microservices.
3. **Car Service:** Responsible for interactions with a MySQL database related to car data.
4. **Client Service:** Manages interactions with a MySQL database containing client-related data.

## Testing

Chrome DevTools, a widely used web development tool, was employed to ensure the proper functionality of the services.

## Running the Project

Follow these steps to run the microservices:

1. Start the Eureka Server.
2. Launch the Gateway.
3. Run the Car Service and Client Service.
4. Access the Eureka interface to view all launched services.

## Video Demo

Check out our video demo for a visual walkthrough of the project.

## JSON Prettify

For improved readability of JSON responses, consider downloading a JSON prettify tool. This will enhance your testing experience by making it easier to interpret and analyze JSON data.

### Advantages of JSON Prettification

- **Readability:** Easily discern the structure and content of JSON responses.
- **Debugging:** Simplifies the identification of issues in JSON data.
- **Documentation:** Facilitates the documentation of API responses for developers.

Enjoy exploring the TP-MICROSERVICES repository! If you encounter any issues or have questions, feel free to reach out.
