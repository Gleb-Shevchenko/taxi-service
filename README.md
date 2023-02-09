# Taxi-Service

This project is a web-application for taxi service, which allows to keep records of drivers and vehicle fleet.

## Project structure

The web-application is built according to 3-tier architecture software design pattern. Thus, the project
contains next layers:
* Presentational - is responsible for user interface operations and informational interchange between user
and application. Contains package *WEB-INF* with *.jsp* files.
* Data layer - stores and performs operations with data. Contains package *dao*.
* Application layer - contains package *controller* with servlets and data required for business logic.

## Technologies

* JDBC
* MySQL
* TomCat
* CSS
* JSP/JSTL
* HTTP

## Application start

Make sure you have MySQL, version of TomCat not higher than 9.0.71 installed. 
Make a fork of this project by this [link][1]. Configure TomCat in your IDE.
By default, you will be redirected on page *login.jsp*. The access to main functionality will be opened
after registration process on *index.jsp* page. Feel free to look through opened links.

[1]: https://github.com/Gleb-Shevchenko/taxi-service.git    "link"
