Description
This project is a backend developed in Spring Boot that allows for the management of sales and products. It provides functionalities to add items to a sale, manage product quantities, and perform CRUD (Create, Read, Update, Delete) operations on the Sale and Product entities. The database used is PostgreSQL.

Features
Add Items to a Sale: Users can add products to an existing sale, reducing the available quantities of those products.
Remove Items from a Sale: Allows users to remove products from a sale, restoring quantities back to the inventory.
CRUD for Products and Sales: Implements standard CRUD operations for the Product and Sale entities, enabling users to create, read, update, and delete records.
API Documentation with Swagger: The API endpoints are documented using Swagger, making it easy to explore and test the available functionalities.
How to Use
Database Configuration:

To use this project, you need to have PostgreSQL installed.
Configure database access in the application.properties file. Example configuration:
properties

  spring.datasource.url=jdbc:postgresql://localhost:5432/your_database
  spring.datasource.username=your_username
  spring.datasource.password=your_password
  Running the Project:

Clone this repository and navigate to the project directory.
Execute the command:

bash
mvn spring-boot:run

The application will be available at http://localhost:8080.

Accessing the API Documentation:
  Access the API documentation via Swagger at http://localhost:8080/swagger-ui.html.
