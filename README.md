
           Makersharks Assessment

1. Project Setup
First, create a new Spring Boot project and set up the necessary dependencies.

2. Entity and Repository
Create a User entity to represent user information and a UserRepository interface to interact with the database.

3. Service Layer
Implement UserService to handle business logic such as user registration and fetching user details.

4. Controller Layer
Create UserController to define REST endpoints /api/user/register and /api/user/fetch.

5. Exception Handling
Implement global exception handling to manage errors gracefully.

6. Security
Basic implementation to secure endpoints (e.g., using HTTPS).


Instructions for Running the Application
To run the application locally:

Ensure you have MySQL installed and running.
Create a database named user_registration_db in MySQL.
Clone the repository from GitHub.
Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
Modify the application.properties file with your MySQL username and password.
Run the application as a Spring Boot application (UserRegistrationApiApplication.java).



Register User
POST /api/user/register


{
  "username": "jane_doe",
  "email": "Makersharks@example.com",
  "password": "securepassword"
}




Fetch User
GET /api/user/fetch

Query Parameter: username=jane_doe

{
  "username": "jane_doe",
  "email": "Makersharks@example.com",
  "password": "securepassword"
}
