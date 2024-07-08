# Student Management System

## Overview

This project is a full-stack CRUD (Create, Read, Update, Delete) web application designed to manage student information. The application features a student form that includes functionality to add, view, update, and delete student records. It utilizes Spring Boot for the backend, Angular for the frontend, Hibernate for ORM, and MySQL for the database.

## Features

- **Add Student**: Allows users to add new student records.
- **View Students**: Displays a list of all students with options to update or delete each record.
- **Update Student**: Enables users to update existing student information.
- **Delete Student**: Allows users to delete a student record from the database.

## Technologies Used

- **Backend**: Spring Boot 2, Hibernate 5
- **Frontend**: Angular 6
- **Database**: MySQL
- **Server**: Apache Tomcat
- **IDE**: Spring Tool Suite (STS) for backend development, Visual Studio Code for frontend development

## Prerequisites

- Java JDK 8 or higher
- Node.js and npm
- MySQL
- Apache Tomcat server

## Setup and Installation

### Backend (Spring Boot)

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the backend directory:**
   ```bash
   cd backend
   ```

3. **Update MySQL configurations:**
   Edit `application.properties` to configure your MySQL database settings.
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/student_db
   spring.datasource.username=root
   spring.datasource.password=password
   spring.jpa.hibernate.ddl-auto=update
   ```

4. **Build and run the backend application:**
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

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, please contact [your-email@example.com].
