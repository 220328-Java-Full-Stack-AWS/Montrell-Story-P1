# Project 1 - Employee Reimbursment System (ERS)

## Executive Summary
The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement. The reimbursement types should have the following options: LODGING, FOOD, TRAVEL


# Tech Stack
 - Java 8
 - Apache Maven
 - PostgreSQL
 - AWS RDS
 - Java Servlets
 - JDBC
 - HTML
 - CSS
 - JavaScript
 - AJAX / Fetch API

# Features
 - Domain objects persisted in relational database
 - Database should be in 3NF
 - CRUD functionality for all domain objects
 - All CRUD functionality accessible via RESTful API
 - Functional web UI to consume RESTful API
 - Validate all user input
 - Unit test coverage for service-layer classes

The persistence-layer system use JDBC to connect to a MySql database. The API-layer utilizes Java servlets to expose a public interface. The front-end view uses HTML/CSS/JavaScript to make an application that can call server-side components in a generally RESTful manner. The middle tier shall follow proper layered architecture, and have reasonable JUnit test coverage of the service layer. Webpages is styled to be functional and readable. 

# User Stories
### Requirements:
#### Guest:
 - As a guest, I can register for a new account
 - As a guest, I can log into my account

#### User:
 - As a user, I can submit a request for reimbursement
 - As a user, I can cancel a pending request for reimbursement
 - As a user, I can view my pending and completed past requests for reimbursement
 - As a user, I can edit my pending requests for reimbursement

#### Stretch Goals:
 - As an admin, I can change a user's role between admin and user


# Add User
![Add User](https://user-images.githubusercontent.com/15221031/168384107-ec6383f6-0d98-4fd2-b32d-f116c86992d2.png)


# Update User


![Update User](https://user-images.githubusercontent.com/15221031/168384385-9c0ca458-ca9a-4c7a-af94-10dc42064465.png)

**Login**
![Login](https://user-images.githubusercontent.com/15221031/168384694-38817dcd-8618-4b66-8b97-23a30ed9416d.png)



**Admin List of Users**
![User List](https://user-images.githubusercontent.com/15221031/168384770-cc3e10fc-9008-4542-b54a-4ecf52bd2203.png)






