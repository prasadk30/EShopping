# EShopping

##Project Overview
EShopping is a demonstration project of an E-Commerce website built using Java, Spring Boot, Spring Security, Thymeleaf, HTML, CSS, Bootstrap, and MySQL database. It features user authentication, product management, and a responsive UI for a seamless shopping experience.

## Technologies Used

- Java 17+
- Spring Boot 3.x
- Spring Data JPA
- Spring Security 6.0
- Hibernate
- MySQL (or any other RDBMS)
- Maven
- RESTful APIs

## Features
1. **User authentication (Registration/Login) with Spring Security.
2. **Role-based access (e.g., Admin and User roles).
3. **Product listing with pagination.
4. **Add, Edit, and Delete products (Admin only).
5. **Shopping cart functionality.
6. **Secure payment integration (future scope).
7. **Responsive design with Bootstrap and Thymeleaf.
8. **Backend powered by Spring Boot, with MySQL for data persistence.

### Future Enhancements
1. **Integration with payment gateways.
2. **Proper User profile management.
3. **Order tracking.

###Contributing
Contributions are welcome! Feel free to fork this project, create a feature branch, and submit a pull request.


## Database Configuration

**Set up a MySQL database

CREATE DATABASE eshopping_db;

**Update application.properties (or application.yml) with your MySQL credentials:
This project uses MySQL as the database. You can configure your own database.
No Need to create tables after Build and Run the Project tables will get automatically created. 
Example configuration for MySQL:

```properties
spring.application.name=EShopping
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=password
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

## Email Configuration
**configure email service for send email from admin side to user. 
spring.mail.host=smtp.gmail.com
spring.mail.username=youremailid@gmail.com
spring.mail.password=********
spring.mail.port=587
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
