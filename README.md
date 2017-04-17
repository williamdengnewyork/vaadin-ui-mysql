# Build a java-based web UI for MySQL with Vaadin framework, integration using Spring JDBC template

This example shows how to build a web UI for an existing MySQL database using plain Java.

>> Tech Stack
- Java based Vaadin wbe UI framework, com.vaadin.ui.UI
- Spring JDBC template
- MySQL 


https://vaadin.com/framework
https://vaadin.com/blog/-/blogs/building-a-web-ui-for-mysql-databases-in-plain-java-

--- MySQL Data creation

CREATE SCHEMA demo;
use demo

CREATE TABLE customers(
    id SERIAL,
    first_name VARCHAR(255),
    last_name VARCHAR(255)
);


INSERT INTO customers(first_name, last_name) VALUES('Bruce', 'Tate');
INSERT INTO customers(first_name, last_name) VALUES('Mario', 'Fusco');
INSERT INTO customers(first_name, last_name) VALUES('Edson', 'Yanaga');
INSERT INTO customers(first_name, last_name) VALUES('Anton', 'Arhipov');
INSERT INTO customers(first_name, last_name) VALUES('Andres', 'Almiray');
