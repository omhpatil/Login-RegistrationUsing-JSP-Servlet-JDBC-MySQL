# Login&RegistrationUsing-JSP-Servlet-JDBC-MySQL
- The project will be a Web-based project to provide a complete Real-Time scenario of the Secure User Authentication.
- Used JSP as a front-end design and Servlet as a back-end configure.
- Used JDBC along with TomCat web-container for Server-side scripting for database operation.
- MySQL is used for database integration for storing user information.

![1](https://github.com/user-attachments/assets/d862f459-7e03-4bc1-a23e-defa2e9c96e2)
![2](https://github.com/user-attachments/assets/f8c032fa-7a79-4e22-a108-b3203867da56)
![3](https://github.com/user-attachments/assets/fb95996d-b385-4047-aca3-661c4c68d0c8)
![4](https://github.com/user-attachments/assets/fdae9319-7a08-4388-9543-6870535e74ba)
![5](https://github.com/user-attachments/assets/eabc6548-dd5d-4303-8257-f3cf43480f10)
# Project Structure
![Structure](https://github.com/user-attachments/assets/16a434a5-c1e8-40a8-a821-9d6372ccc25d)

# Features
- Handles HTTP GET and POST requests.
- Responds with dynamic content based on the request.
- Example use case for learning servlet functionality.

# Prerequisites
To run this servlet program, ensure you have the following:
- Java Development Kit (JDK) version 8 or higher
- Apache Tomcat or MySQL Connector
- An Integrated Development Environment (IDE) like Eclipse, IntelliJ IDEA, or Visual Studio Code (optional but recommended)

# Technologies Used
- Programming Language: Java
- Servlet Container: Apache Tomcat
- Database: MySQL

# Database Setup
Create User Table to store user data, create the following table in your database:

CREATE TABLE user (
    id INT AUTO_INCREMENT PRIMARY KEY,
    uname VARCHAR(100) NOT NULL,
    upswd VARCHAR(100) NOT NULL,
    uemail VARCHAR(100) NOT NULL UNIQUE,
    umob VARCHAR(15) NOT NULL
);

This table structure stores user information such as username, password, email, and mobile number. Ensure the id column auto-increments to generate a unique identifier for each user. The uemail field is set to be unique to avoid duplicate email entries.
