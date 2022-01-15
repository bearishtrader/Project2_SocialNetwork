# Project2_SocialNetwork
Project 2 - Social Network for Revature

Social network app with Angular front-end and Spring Boot/MVC/Data back-end.

Users can register, login, edit/update their prodile and post text, images or YouTube video links in addition to commenting on and liking each others posts. There is a password reset feature via e-mail (Spring Mail) in the case of forgotten passwords and password encryption (Spring Security Crypto stand-alone module).

#Technologies Used
- Java with Spring Boot/MVC/Data/Mail for back end
- Angular/Typescript for front end
- Frontcontroller design pattern with JPA repositories for the DAO (Data Access Object) layer with a Service layer.
- The JPA (Java Persistence API) has annotations which are used within the data object models to describe entity relationships and how the entities should be bound to the underlying database tables, thus no explicit SQL queries were required as with Project 1's DAO layer.
- H2 in-memory database for day-to-day development and testing and Postgres DBMS for deployment
- JUnit and Mockito for unit and integration testing
- JPATest for repository integration testing 
- MVCTest for Web API endpoint integration testing
- Selenium web automation tool with Cucumber/Gherkin BDD (Behavior Driven Development) framework for end-to-end testing.
- Spring Mail with Amazon SES (Simple Email Service) used to send password reset e-mail
- Spring Security Crypto stand-alone module (e.g. spring-security-crypto) for password encryption
- Deployed to AWS EC2 instance via Maven build

#Contributors
Brady Westveer (https://github.com/bradywestveer-revature)
David Helfer  (https://github.com/DavidHelfer1616)

#Repositories
Front-end:  https://github.com/bearishtrader/project2-frontend.git 
Back-end:  https://github.com/bearishtrader/project2-backend.git
End-to-end testing:  https://github.com/bearishtrader/project2-e2e.git
