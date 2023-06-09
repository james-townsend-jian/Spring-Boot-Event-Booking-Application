# Spring-Boot-Event-Booking-Application

## Introduction
Welcome to the Java Spring Boot Event Booking web application project! I wanted to start this project to personally demonstrate my ability to use Java Spring Boot to build a simple event booking web application.  The project consists of a fully functional web application that allows users to view upcoming events, create new events, and book tickets for those events. The application is built using Java Spring Boot, which is a popular framework for building enterprise web applications.  Throughout the project, I hope to demonstrate my grasp on fundamental concepts of Spring Boot, including building controllers, views, and models. I will also handle user authentication and authorization, validate user input, and persist data using a relational database.

## Project Requirements

**User Registration:**
Users should be able to register by providing their basic information (name, email, password).
User registration should be validated to ensure that all required fields are filled and that the email is unique.

**User Authentication:** 
Users should be able to log in using their email and password.
Passwords should be encrypted and stored securely.

**Event Creation:** Authenticated users should be able to create events by providing event details (title, description, date/time, location).
Event creation should be validated to ensure that all required fields are filled.

**Event Booking:**
Authenticated users should be able to book events.
Users should be able to see a list of events and select an event to book.
Users should be able to select the number of tickets they want to purchase.
Event booking should be validated to ensure that the requested number of tickets is available.

**Event Management:** 
Event creators should be able to manage their events (edit, delete).
Event deletion should prompt the user for confirmation before deleting.

**Displaying Event Details:** Users should be able to view event details such as title, description, date/time, location, and available tickets.

**Pagination:** Events should be paginated to improve performance and user experience.

**Error Handling:** The application should handle errors gracefully and provide meaningful error messages to the user.

**User Dashboard:** Authenticated users should be able to view a dashboard showing their upcoming events and tickets.

**Deployment:** The application should be deployable to a cloud platform like Heroku or AWS.
These project requirements are simple enough for a junior developer to implement and will showcase their ability to create a basic Spring Boot web application for event registration.

## Spring Boot Dependencies
**Spring Boot Starter Web:** This dependency provides the necessary components for building web applications using Spring MVC.

**Spring Boot Starter Thymeleaf:** This dependency provides the Thymeleaf template engine, which is a popular choice for building web pages in Spring Boot.

**Spring Boot Starter Data JPA:** This dependency provides the necessary components for working with relational databases using the Java Persistence API (JPA).

**Spring Boot Starter Security:** This dependency provides the necessary components for adding security to your Spring Boot application.

**H2 Database:** This is an in-memory database that can be used for development and testing purposes.

**Spring Boot DevTools:** This dependency provides useful development tools that can help with hot reloading, among other things.
