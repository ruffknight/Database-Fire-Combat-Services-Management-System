# Fire Combat Services Management System - Database

![Database Fire Combat](https://i.ibb.co/m9d5V9F/database.png)

## Introduction

The **Fire Combat Services Management System Database** project entails the design of a database for fire combat services and development of a web application for user interaction. This project involves the conception of a database schema, integrity constraints, SQL queries.

## Project Overview

The project revolves around the creation of a database schema and the establishment of integrity constraints for a Fire Combat Services Management System. This system is designed to manage emergency events such as forest fires in various locations. The system encompasses events, emergency calls, rescue processes, vehicles, entities, and more. 
A prototype web application was developed to interact with the database, enabling users to perform various operations such as insertion, deletion, and listing of entities.
Additionally, the project involved implementing SQL queries to retrieve relevant information from the database.

### Technology Stack

- The database schema and queries were implemented using the PostgreSQL database management system.
- The prototype web application was developed using PHP and HTML.

### Project Tasks

The Prototype Web Application allows users to:
  a) Insert and remove locations, emergency events, rescue processes, vehicles, and entities.
  b) Insert, edit, and remove combat vehicles, support vehicles, and rescue vehicles.
  c) List rescue processes and vehicles.
  d) Associate rescue processes with vehicles and rescue processes with emergency events.
  e) List vehicles activated in a rescue process.
  f) List rescue vehicles activated in rescue processes originating from a specific fire location.

## Prerequisites

To run this project, ensure you have the following prerequisites:

1. **PostgreSQL Database:** Install the PostgreSQL database management system on your system. You can download and install it from the [official PostgreSQL website](https://www.postgresql.org/download/) or use package managers available for your platform.
   
2. **Web Server (Optional for Prototype):** If you intend to run the prototype web application, you'll need a web server such as Apache. You can install Apache and set up a PHP environment on your system.

## Instructions

To run the web application, follow these steps:

1. Place the contents of the "web" directory in the appropriate directory served by your web server.
2. Open a web browser and navigate to the following URL:
   ```
   http://localhost/path/to/web/index.html
   ```
   Replace "localhost/path/to/web" with the actual URL path where you placed the web folder.

3. Explore the web application.

The **Fire Combat Services Management System** project demonstrates effective database design, integrity constraint implementation, SQL query execution, and interactive web application development. This integrated solution provides a comprehensive approach to managing emergency scenarios, showcasing practical usage scenarios and enabling efficient data management. Thank you for checking this project!
