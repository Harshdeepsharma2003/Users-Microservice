The Harshdeep User Service is a Spring Boot application designed to manage user-related functionalities for the Harshdeep project. This service provides RESTful APIs to create, retrieve, and manage user data efficiently. It leverages Spring Data JPA for database interactions and includes exception handling to manage errors gracefully.

Features
User Management:

Create new users
Retrieve user details by ID
Fetch all users
Exception Handling:

Custom exception handling for resource not found scenarios.
Database Integration:

Utilizes MySQL for persistent storage of user data.
Supports JPA for easy database operations.
Annotation Processing:

Uses Lombok for reducing boilerplate code in model classes.
Technologies Used
Java 21
Spring Boot 3.4.1
Spring Data JPA
MySQL
Lombok
Maven for dependency management
Getting Started
Prerequisites
Java 21 or higher
Maven
MySQL Database
Installation
Clone the Repository:

bash

Verify

Open In Editor
Run
Copy code
git clone https://github.com/Harshdeepsharma2003/User-microservice.git
cd User-microservice
Configure Database:

Set up a MySQL database and update the application.properties or application.yml file with your database credentials.
Build the Project:

bash

Verify

Open In Editor
Run
Copy code
mvn clean install
Run the Application:

bash

Verify

Open In Editor
Run
Copy code
mvn spring-boot:run
API Endpoints
Create User:

POST /harshdeep1/users
Request Body: JSON representation of HarshdeepUser 
Get Single User:

GET /harshdeep1/users/{userId}
Get All Users:

GET /harshdeep1/users
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch-name).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch-name).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the Spring Boot community for their excellent documentation and support.
Special thanks to the contributors who help improve this project.
Feel free to modify any sections to better fit your project's specifics or to add any additional information that may be relevant!
