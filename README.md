# capstone-project-3900capstone

## Overview
Our team has worked on creating a centralised platform for UNSW students to easily and securely buy second-handed textbooks. For users, in addition to purchasing textbooks, our website also provides personalised recommendations based on their major that they have provided us. For admins, we provide analytics which will help them when managing stocks.

## Goal
Our team's common goal is to create a second-hand book trading platform belonging to the University of New South Wales.This platform allows students to freely buy and search for second-hand books on the platform according to their own requirements, so as to quickly get useful information. The platform will also achieve maintainability, practicality, security, and aesthetics.

## Design
To design the platform, we split the work to front end and back end. Firstly, for the front end, our team decided to use pure html, css and javascript and use bootstrap framework to make our website much better. Secondly, for the backend, our team decided to use Springboot, which is a Java framework. The next step is to choose the sql engine and design the tables of the database and the relationship among sql tables. Our team uses InnoDB of Mysql to be the SQL engine. Then our team needs to combine the back end and front end, which is implemented by Thymeleaf, a model engine that can be used in Springboot. After that, the programming environment needs to be set up. Our team uses Intellij IDEA to be our IDE and set the environment inside, which uses maven to manage the project.

## Main Functionalities
- User authentication
  - registration
  - login
  - update profile
  
 - User
    - textbook recommendation
   - book listing/searching/filtering
   - cart
   - payment
   - feedback
  
 - Admin
   - Analytics
   - Inventory management
