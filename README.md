🚀 User Management System – Spring Boot

A User Management System built using Spring Boot that provides secure user authentication and role-based access control. This project is designed following industry best practices and is suitable for real-world applications, interviews, and resume projects.

📌 Features
🔐 User Registration & Login
🔑 JWT-based Authentication & Authorization
👥 Role-based Access (ADMIN / USER)
🧾 Secure Password Encryption (BCrypt)
🌐 RESTful APIs
🛡️ Spring Security Integration
📦 Maven Project Structure
📄 Clean & Maintainable Code

🛠️ Tech Stack
Technology         	Description
Java	              Java 17
Spring Boot	        Backend Framework
Spring Security	    Authentication & Authorization
JWT	                Token-based Security
Hibernate / JPA	    ORM
MySQL             	Database
Maven	              Dependency Management
Postman	            API Testing

📂 Project Structure
user-management-springboot
│
├── src/main/java
│   └── com.example.usermanagement
│       ├── controller
│       ├── service
│       ├── repository
│       ├── model
│       ├── security
│       └── UserManagementApplication.java
│
├── src/main/resources
│   ├── application.properties
│   └── static/
│
├── pom.xml
└── README.md

🔐 API Endpoints
🔹 Authentication APIs
Method	       Endpoint	         Description
POST         	/auth/register  	Register new user
POST	       /auth/login      	Login and get JWT token

🔹 User APIs
Method	     Endpoint     	Access
GET	          /users      	ADMIN
GET	         /users/{id}	  ADMIN
DELETE    	/users/{id}	    ADMIN

⚙️ Configuration
Database Configuration (application.properties)
spring.datasource.url=jdbc:mysql://localhost:3306/userdb
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
jwt.secret=your_secret_key
jwt.expiration=86400000

▶️ How to Run the Project
Prerequisites
Java 17+
Maven
MySQL
Spring Tool Suite / IntelliJ / Eclipse

Steps
Clone the repository
git clone https://github.com/PawanDhole/user-management-springboot.git


Import project as Maven Project
Configure database in application.properties
Run:
mvn spring-boot:run
OR
Run UserManagementApplication.java

🧪 Testing APIs
Use Postman:
Register user
Login → get JWT token
Pass token in header:
Authorization: Bearer <JWT_TOKEN>

🎯 Use Cases
Learning Spring Boot Security
JWT Authentication implementation
College projects
Interview preparation
Production-ready starter template

👨‍💻 Author
Pawan Dhole
💼 Java | Spring Boot Developer
🔗 GitHub: https://github.com/PawanDhole

⭐ If you like this project
Give it a ⭐ on GitHub — it really helps!

