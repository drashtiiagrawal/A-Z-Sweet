# online-shopping

This is an online shopping project using Spring Boot,Spring web-flow, Spring Rest Services and Hibernate. In this project we also used Spring Security with java and annotation configuration

## Requirements

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

# Runnig this project

2. create databases schema in mysql - **online_shopping_db**
3. edit **username** and **password** in **applicaton.properties** file
4. Run Project One time using Spring boot command - **mvn spring-boot:run** or using eclipse IDE run as Java Application
5. Run this Query in mysql

```sql
insert into online_shopping_db.user_detail(contact_number,email,enabled,first_name,last_name,password,role) values ('9876543210','admin@gmail.com',true,'admin','admin','$2a$10$6UVHQoHhpoYZxBB.k9r.deSLTT0RD1Yk8GdggRywGw0Snr8syRDtG','ADMIN')
```

**Password = 123456(in encoded Form)**

6. Then Again run project using boot
7. create user by signup

### Guides

The https://spring.io/[spring.io] site contains several guides that show how to use Spring
Boot step-by-step:

- https://spring.io/guides/gs/spring-boot/ [Building an Application with Spring Boot] is a
  very basic guide that shows you how to create a simple application, run it and add some
  management services.
- https://spring.io/guides/gs/actuator-service/ [Building a RESTful Web Service with Spring
  Boot Actuator] is a guide to creating a REST web service and also shows how the server
  can be configured.
- https://spring.io/guides/gs/convert-jar-to-war/ [Converting a Spring Boot JAR Application
  to a WAR] shows you how to run applications in a web server as a WAR file.
