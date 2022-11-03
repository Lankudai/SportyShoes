# Portal for SportyShoe.com

# Table of Contents:
* Aim of Project
* About the Project
* Technologies Used
* Flowchart of the Application
* Core Concept Used in the Project
* Screenshot(OUTPUT)

# Aim of Project:
 To develop a prototype of appliaction of making an E-Commerce Website for SportyShoes.
 
 # About the Project:
  This application is designed and developed as an e-commerce portal sportyshoes.com for a walk-in store. This system allows Administrator to create(add), read(list),   update and delete the customers of the application, categories and products of the application and to see the orders by customers. This project helps the       administrator to manage the products and the customers well. The customer can login into the system as well as view the products added in the portal by the authorized admin.
  
  This project uses Spring Boot for Model and Controller Implementation Availaible apis are -

 /shoe (CRUD)
 /purchaseReport (CRUD)
 /shoe/all
 /purchaseReport/(category|all|dop)
 Current Implementation relies simply on String for storing order list.

 It can be extended to utilize many-to-many relationship b/w Shoe and PurchaseReport Entities.

 Also for admin authentication spring-security-starter has been used with credentials saved in application.properties file.
 

# Technologies Used:
 
  * Java	1.8
  * Spring Boot	2.2.10
  * Lombok	---
  * Swagger-ui	2.7.0
  * H2	---
  * JPA	---
  8 Spring Security Starter	---
