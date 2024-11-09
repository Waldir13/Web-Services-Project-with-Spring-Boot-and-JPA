# Web Services Project with Spring Boot and JPA  

This project was developed as part of a study on creating RESTful APIs using **Spring Boot** and **JPA (Java Persistence API)**. It implements a complete data management system, including CRUD functionalities, logical layer structuring, and exception handling.  

<p align="center">
  <img src="https://raw.githubusercontent.com/Waldir13/Web-Services-Project-with-Spring-Boot-and-JPA/master/course/images/1.png" alt="Project Image" width="500">
</p> 

## Features Developed  

### Project Configuration  
- Initial setup of a Spring Boot project in Java.  
- Integration with the H2 in-memory database for testing.  

### Domain Model  

<p align="center">
  <img src="https://raw.githubusercontent.com/Waldir13/Web-Services-Project-with-Spring-Boot-and-JPA/master/course/images/2.png" alt="Project Image" width="600">
</p>

- Creation of entities to represent the domain objects.  
- Mapping entities with **JPA**.  

### Logical Layers  

<p align="center">
  <img src="https://raw.githubusercontent.com/Waldir13/Web-Services-Project-with-Spring-Boot-and-JPA/master/course/images/4.png" alt="Project Image" width="500">
</p>


- Implementation of **Resource**, **Service**, and **Repository** layers, following best architectural practices.  

### Database  
- Configuration and automatic population of the database with test data.  

### CRUD Operations  
- Implementation of core operations:  
  - **Create**: Add new records to the database.  
  - **Retrieve**: Fetch records using different criteria.  
  - **Update**: Update existing data.  
  - **Delete**: Remove records from the database.  

### Exception Handling  
- Custom error handling layer to provide clear and structured responses.  

## Technologies Used  

| Technology      | Description                      |  
|------------------|----------------------------------|  
| **Spring Boot**  | Framework for building Java applications. |  
| **JPA / Hibernate** | ORM for database interaction.         |  
| **H2 Database**  | In-memory database for testing. |  
| **Maven**        | Dependency management.          |  
| **Java 17**      | Programming language.           |  
