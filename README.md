# HealthCare System - JEE

This project is a Java-based web application designed to manage and streamline healthcare operations. Built using Java Enterprise Edition (JEE), the HealthCare System provides functionalities for handling patient information, managing appointments, and facilitating communication between patients and healthcare providers.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

HealthCare System is an integrated platform aimed at automating healthcare services. It enables healthcare providers to manage patient records, book appointments, and monitor patient histories efficiently. Designed with scalability and security in mind, this system can support a range of healthcare providers, from small clinics to large hospitals.

## Features

- **Patient Management**: Store and manage patient information securely.
- **Appointment Scheduling**: Schedule, update, and cancel appointments.
- **Doctor Portal**: A dedicated portal for doctors to view patient information and manage schedules.
- **Patient Portal**: Allows patients to view their records, book appointments, and communicate with healthcare providers.
- **Admin Dashboard**: For managing system users, doctors, and overall data analytics.
  
## Technologies Used

- **Java EE**: Backend logic and services
- **Servlets**: For handling HTTP requests and responses
- **JSP (JavaServer Pages)**: For dynamic web pages
- **MySQL**: Database for storing user and medical data
- **Apache Tomcat**: For server deployment

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/PyaeLinn01/HealthCare-System-JEE.git
   ```

2. **Set up the database**:

   - Create a MySQL database named `healthcare_system`.
   - Import the provided SQL script (`database.sql`) to set up tables and initial data.

3. **Configure the database connection**:

   - Open the project in your preferred IDE (e.g., Eclipse, IntelliJ).
   - In the database configuration file, update the MySQL connection details (username, password, etc.).

4. **Deploy the application**:

   - Run the application on an Apache Tomcat server.
   - Access the application by navigating to `http://localhost:8080/HealthCare-System-JEE` in your web browser.

## Usage

After setting up, access the system as an admin, doctor, or patient. Each user role has specific permissions, such as managing appointments, viewing medical history, or updating records. Customize features as needed to fit different healthcare settings.

## Contributing

Contributions are welcome! If you want to contribute, please fork the repository and create a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---
