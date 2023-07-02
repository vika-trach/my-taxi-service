# taxi-service
It is a simple web application that uses Java, JDBC, Servlets, OOP and SOLID. 
The project focuses on basic CRUD operations and also uses one-to-one, one-to-many and many-to-many relationships in the database.
MySQL was used as a database management system. The application also includes user authentication and registration functions.

### Functionality
* register a driver
* log in and log out
* create/read/update/delete a driver
* create/read/update/delete a car
* create/read/update/delete a manufacturer
* show all drivers
* show all cars
* show all manufacturers

###   Project structure
Project has N-Tier Architecture:

*   Controller - accepts requests from the user, passes them to the service layer, and returns jsp pages in response
*   Service - accepts requests from the controller, passes them to the DAO layer, and performs all business logic
*   DAO - accepts requests from the service, passes them to the DB, and executes all sql queries

### Technologies used:
* Java 11 
* JDBC 
* MySQL
* Maven 
* Tomcat (9.0.76)
* JSP
* HTML
* SOLID Principles Java
* Dependency injection

### To run this application, follow the steps below:
1. [ ] Clone this project from GitHub
2. [ ] Download Apache Tomcat version 9.x.x from the official Apache Tomcat website.
3. [ ] Create a database using either a local MySQL installation or a remote database.
4. [ ] Write your properties to ConnectionUtil class:

![Знімок екрана 2023-07-02 о 21.58.14.png](..%2F..%2F..%2F..%2Fvar%2Ffolders%2Ffr%2Fxw2dbyf167n6bp8cfyjrclt00000gp%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_FlBu4i%2F%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-07-02%20%D0%BE%2021.58.14.png)
5. [ ] Run project.