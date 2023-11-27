# Hospital Management System

This is a Java-based Hospital Management System designed to facilitate the management of patients, doctors, and appointments within a hospital setting. The system utilizes a MySQL database to store and retrieve information.

## Prerequisites

Before running the application, ensure that you have the following installed:

- Java Development Kit (JDK)
- MySQL Database
- MySQL Connector/J (JDBC Driver)

## Configuration

1. **Database Configuration:**
   Update the database connection details in the `HospitalManagementSystem` class:

   ```java
   private static final String url = "jdbc:mysql://localhost:3306/hospital";
   private static final String username = "root";
   private static final String password = "Admin@123";
   
## Usage

1. Compile: javac HospitalManagementSystem.java
2. Run: java HospitalManagementSystem
3. Operations:
      Add Patient
      View Patients
      View Doctors
      Book Appointment
      Exit
   
## Features
    Add Patient: Add a new patient.
    View Patients: Display all patients.
    View Doctors: Display all doctors.
    Book Appointment: Schedule appointments, considering doctor availability.
      
## Notes
    MySQL database required.
    Date format for appointments: "YYYY-MM-DD".
      
## Contribution
    Feel free to explore and modify. Contributions are welcome!
