# Airline Booking System

This project is a microservice-based backend system built with Node.js, Express, MySQL (using Sequelize ORM), and RabbitMQ. It facilitates the booking of flights through a RESTful API and utilizes a messaging queue system for efficient communication between microservices.

## Features

- **Microservice Architecture**: The system is designed using microservices like API, Booking, and Notification Services, enhancing scalability and modularity.
- **RESTful APIs**: Provides endpoints for seamless communication between clients and the backend system.
- **CRUD Operations**: Supports Create, Read, Update, and Delete operations for managing flight bookings and related data.
- **Authentication & Authorization**: Implements secure access control mechanisms for authenticated and authorized users.
- **Cron Jobs**: Includes scheduled tasks for automated processes within the system.

## Technologies Used

- **Node.js**: Backend server environment for JavaScript runtime.
- **Express.js**: Web application framework for Node.js used to create APIs.
- **MySQL with Sequelize**: Database management system and ORM for interacting with the database.
- **RabbitMQ**: Messaging queue system using Publisher-Subscriber model for efficient communication.
- **Other Libraries**: Any additional libraries or dependencies used in the project.

## Getting Started

As this project consists of multiple microservices, each service has its own repository and setup instructions. Below are the steps to set up and run each microservice:

1. **[API Search Service](https://github.com/ArunRawat404/Flight-Service)**:

   - Clone the API Search Service repository.
   - Follow the README instructions in the API Search Service repository for setup and deployment.

2. **[API Gateway](https://github.com/ArunRawat404/Flight-API-Gateway)**:

   - Clone the API Gateway repository.
   - Follow the README instructions in the API Gateway repository for setup and deployment.

3. **[Booking Service](https://github.com/ArunRawat404/Flight-Booking-Service)**:

   - Clone the Booking Service repository.
   - Follow the README instructions in the Booking Service repository for setup and deployment.

4. **[Notification Service](https://github.com/ArunRawat404/Flight-Notification-Service)**:
   - Clone the Notification Service repository.
   - Follow the README instructions in the Notification Service repository for setup and deployment.

> Note: Each microservice might have its own specific setup requirements and configuration instructions. Please refer to the README files in their respective repositories for detailed information.

## High Level System Design

![High Level System Design](Airline_management_system_high_level_design.png)
