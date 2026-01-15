Task 2 – Spring Boot REST API (Products)

This project is a simple REST API made with Spring Boot.
It is used to manage products and supports basic CRUD operations (create, read, update, delete).

The project is written in Java and uses Spring Boot with Spring Web and Spring Data JPA.
An H2 in-memory database is used to store the data.
Swagger UI is included to test and view all the API endpoints.

To run the project, open it in IntelliJ IDEA and run the main class Task2Application.
After starting the application, it will run on http://localhost:8080
.

Swagger UI can be used to test the API.
Open the following link in your browser: http://localhost:8080/swagger-ui/index.html
.
With Swagger, you can get all products, create a new product, update a product, and delete a product.

The project uses an H2 database for testing.
The H2 console is available at http://localhost:8080/h2-console
.
To log in, use jdbc:h2:mem:testdb as the JDBC URL, sa as the username, and leave the password empty.
You can view the product table and check the stored data from the console.
![h2-select-product-result.png](screenshots/h2-select-product-result.png)
