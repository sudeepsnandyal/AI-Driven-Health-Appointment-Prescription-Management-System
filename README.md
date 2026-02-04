📌 Project Overview

The AI-Driven Health Appointment & Prescription Management System is a full-stack healthcare management application designed to digitize and streamline hospital workflows. The system enables efficient doctor and patient management, appointment scheduling, and AI-based prescription generation through a clean, form-based user interface.

This project is built using Spring Boot for backend development and HTML/CSS for the frontend, following a layered architecture to ensure scalability, maintainability, and clarity of code.

🚀 Features

Doctor and patient registration with separate database tables

Appointment booking with doctor–patient relationship validation

AI-based prescription recommendation using symptom analysis (rule-based engine)

View patient prescription history

Clean, multi-page HTML/CSS frontend with form-to-backend mapping

Full CRUD operations using Spring Data JPA

In-memory H2 database for easy setup and testing

🛠️ Tech Stack

Backend: Java 17, Spring Boot, Spring MVC, Spring Data JPA

Frontend: HTML5, CSS3

Database: H2 (in-memory)

Build Tool: Maven

IDE: Eclipse / Spring Tool Suite

🏗️ Architecture

The project follows a layered architecture:

Controller Layer: Handles HTTP requests and form submissions

Service Layer: Contains business logic and AI prescription engine

Repository Layer: Manages database operations using JPA

Model Layer: Defines entities such as User, Doctor, Patient, Appointment, and Prescription

Frontend Layer: Multi-page HTML/CSS UI mapped to backend endpoints

🤖 AI Module

The AI component is implemented as a rule-based prescription engine that analyzes patient symptoms (fever, cold, headache, etc.) and suggests appropriate medicines. This module is designed to be easily replaceable with a machine-learning model in future enhancements.

▶️ How to Run the Project

Clone or download the repository

Import the project into Eclipse as an existing Maven project

Run the HealthcareApplication.java file

Open the browser and navigate to:

http://localhost:8080/home.html


Use the UI to add doctors, patients, create appointments, and generate prescriptions

📈 Future Enhancements

Replace H2 with MySQL database

Add JWT-based authentication and role-based authorization

Develop React/Angular frontend

Enhance AI module using machine-learning models

Containerize the application using Docker

👤 Author

Sudeep S
Java Full Stack Developer
