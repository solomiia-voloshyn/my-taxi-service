# 🚖 Taxi-Service 🚖

### 📄 Project description:

A simple web-application that supports authentication, registration and other CRUD operations.

###  Current project functionality:
- register as driver;
- login as driver;
- create/update/delete a driver;
- display all drivers
- create/update/delete a car;
- display all cars;
- create/update/delete a manufacturer;
- display all manufactures;
- add a driver to a car;
- display all cars for currently login driver;

### 📂 Project structure:

#### java/
- controller - servlets classes;
- dao - classes responsible for CRUD operations with DB;
- exception - custom exceptions;
- lib - custom implementation of field injector, annotations;
- model - model classes - Car, Driver and Manufacturer;
- service - classes for connecting dao with controllers;
- util - class for connection with DB;
- web.filter - authentication filter;

#### resources/
- init_db.sql - file containing SQL queries;

#### wepapp/
- WEB-INF - jsp pages and corresponding css files;
- web.xml - contains mapping for servlets and endpoints;

#### other
- Pom.xml - contains maven build configs and dependencies;

### ⚙️ Used technologies and libraries:

- Java 19
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- Javax Servlet
- JSP
- JSTL
- HTML/CSS
- Checkstyle plugin

### 📄 How to install the project

- Clone the repo;
- Install MySQL;
- Configure Apache Tomcat version (IMPORTANT): 9.0.5;
- Copy and run SQL script from resources/init_db.sql in order to create a schema and tables for the project;
- Configure util/ConnectionUtil.java with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- Run and enjoy the app 😃
