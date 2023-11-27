# Hospital Management System

This is a simple Java program for a Hospital Management System using a MySQL database for storing patient information, doctor details, and appointments. The system allows users to add patients, view patients, view doctors, and book appointments.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)


## Prerequisites

- Java Development Kit (JDK)
- MySQL Database Server
- MySQL Connector/J JDBC Driver

## Setup

1. Install the Java Development Kit (JDK) on your system.

2. Set up a MySQL Database Server. Create a database named `hospital_management_system`.

3. Update the database connection details in the code:

   ```java
   private static final String url = "jdbc:mysql://localhost:3306/yourDatabaseName";
   private static final String username = "root";
   private static final String password = "MySQLPassword";


## Usage

1. Run the `HospitalManagementSystem` class.
The program provides a simple text-based interface for interacting with the Hospital Management System. Follow the on-screen instructions to add patients, view patients, view doctors, and book appointments.


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

This project uses the MySQL database for data storage.
Special thanks to the [MySQL](https://www.mysql.com/) and [Java](https://www.oracle.com/java/) communities.
