# Project2_SocialNetwork
<h3>Project 2 - Social Network for Revature</h3>

  Social network app with Angular front-end and Spring Boot/MVC/Data back-end.

  Users can register, login, edit/update their prodile and post text, images or YouTube video links in addition to commenting on and liking each others posts. 
  There is a password reset feature via e-mail (Spring Mail) in the case of forgotten passwords and password encryption (Spring Security Crypto stand-alone module).

<h3>Technologies Used</h3>
  - Java with Spring Boot/MVC/Data/Mail for back end<br/>
  - Angular/Typescript for front end<br/>
  - Frontcontroller design pattern with JPA repositories for the DAO (Data Access Object) layer with a Service layer.<br/>
  - The JPA (Java Persistence API) has annotations which are used within the data object models to describe entity relationships and how the entities should be bound to the underlying database tables, thus no explicit SQL queries were required as with Project 1's DAO layer.<br/>
  - H2 in-memory database for day-to-day development and testing and Postgres DBMS for deployment<br/>
  - JUnit and Mockito for unit and integration testing<br/>
  - JPATest for repository integration testing<br/>
  - MVCTest for Web API endpoint integration testing<br/>
  - Selenium web automation tool with Cucumber/Gherkin BDD (Behavior Driven Development) framework for end-to-end testing.<br/>
  - Spring Mail with Amazon SES (Simple Email Service) used to send password reset e-mail<br/>
  - Spring Security Crypto stand-alone module (e.g. spring-security-crypto) for password encryption<br/>
  - Deployed to AWS EC2 instance via Maven build<br/>

<h3>Contributors</h3>
  Brady Westveer (https://github.com/bradywestveer-revature)<br/>
  David Helfer  (https://github.com/DavidHelfer1616)<br/>

<h3>Repositories</h3>
  Front-end:  https://github.com/bearishtrader/project2-frontend.git<br/>
  Back-end:  https://github.com/bearishtrader/project2-backend.git<br/>
  End-to-end testing:  https://github.com/bearishtrader/project2-e2e.git
