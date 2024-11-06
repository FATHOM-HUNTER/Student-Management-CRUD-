# Student Management System

## Overview

This project is a full-stack CRUD (Create, Read, Update, Delete) web application designed to manage student information. The application features a student form that includes functionality to add, view, update, and delete student records. It utilizes Spring Boot for the backend, Angular for the frontend, Hibernate for ORM, and MySQL for the database.

## Features

- **Add Student**: Allows users to add new student records.
 ![image](https://github.com/FATHOM-HUNTER/Student-Management-CRUD-/assets/88205680/73dba853-5b66-4755-896c-9fc11be7d0c7)

- **View Students**: Displays a list of all students with options to update or delete each record.
 ![image](https://github.com/FATHOM-HUNTER/Student-Management-CRUD-/assets/88205680/18747f8b-c2a3-444d-bf9c-d8531980b994)

- **Update Student**: Enables users to update existing student information.
 ![image](https://github.com/FATHOM-HUNTER/Student-Management-CRUD-/assets/88205680/bb7866fe-7c79-47b7-aaae-27184bf887ef)

- **Delete Student**: Allows users to delete a student record from the database.
 ![image](https://github.com/FATHOM-HUNTER/Student-Management-CRUD-/assets/88205680/1f4e58d7-9d63-4198-a180-88004e4321df)
 

## Technologies Used

- **Backend**: Spring Boot 2, Hibernate 5
- **Frontend**: Angular 6
- **Database**: MySQL

## Prerequisites

- Java JDK 8 or higher
- Node.js and npm
- MySQL

## Setup and Installation

### Backend (Spring Boot)

1. **Navigate to the backend directory:**
   ```bash
   cd backend
   ```

2. **Update MySQL configurations:**
   Edit `application.properties` to configure your MySQL database settings.
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/student_db
   spring.datasource.username=root
   spring.datasource.password=password
   spring.jpa.hibernate.ddl-auto=update
   ```

3. **Build and run the backend application:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend (Angular)

1. **Navigate to the frontend directory:**
   ```bash
   cd frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the frontend application:**
   ```bash
   ng serve
   ```

4. **Access the application:**
   Open your web browser and navigate to `http://localhost:4200/`.

## Usage

- **Add Student**: Click on the "Add Student" link to open the student creation form. Fill in the required details and submit.
- **View Students**: Click on the "View Students" link to see the list of students. Each student record has options to update or delete.
- **Update Student**: Click on the "Update" link next to a student record, modify the details, and save.
- **Delete Student**: Click on the "Delete" link next to a student record to remove it from the database.
