
![Logo](https://img.freepik.com/premium-vector/taxi-service-badge-taxi-map-pointer-vector-icon-for-business-and-advertising-public-transport-design_435184-1169.jpg)


# Taxi-Service

This web project is Taxi-Service simulator.

## Features

- Authentication
- Create and delete car manufacturer
- Create and delete cars
- Create and delete drivers
- Add drivers to specific cars
- View all cars belonging to the current driver
- View all cars, drivers, manufacturers

## Structure

- Controller: Servlets that handle HTTP requests and responses
- DAO: Data Access Object interfaces and their implementations
- Filter: Servlet Filters used to intercept requests and responses
- Model: Plain Old Java Objects (POJOs) that represent data
- Service: Service interfaces and their implementations that perform business logic
- Util: Utility class used in a project to create a database connection
- Resources: Non-Java files such as database scripts and configuration files
- Webapp: Contains web resources such as JSP files
- WEB-INF: Contains configuration files for the web application
- Views: Contains JSP files used as views in the application for cars, drivers, manufacturers, authentication

## Getting started

Please have IntelliJ IDEA Ultimate or ability to adapt following steps on your own.

You will also need: Tomcat 9.0.50 - 9.0.73, Java SDK 11+, maven 3.8.0+, SQL DBMS (tested on MySQL).

- Clone the project repository to your local machine
- Run the SQL script located in `src/main/resources/init_db.sql` to initialize the database
- Replace the values of the `URL`, `USERNAME`, `PASSWORD` and `JDBC_DRIVER` properties with the appropriate values for your database setup
- Build the project using Maven: `mvn clean install`
- Deploy the generated WAR file to servlet container such as Tomcat

When you deploy the project to Tomcat, specify the link  `http://localhost:8080/taxi-service`, press the fix button below and select war explored and in the application context remove the value until /.

- Press run in your IDE :)

## Used Technologies

- `Java v11+`
- `Maven v3.8.0`
- `MySQL v8.0.22`
- `Java Servlets v4.0.1`
- `TomCat v9.0.73`

## Authors

Turchin Yuriy

