# Spring Boot

### What is Spring Boot?
Spring Boot is an open source Java-based framework used to create a micro Service. It provides a good platform for Java developers to develop stand-alone and production-grade spring application that you can just run.



### Advantages
* [x] Easy to understand and develop spring applications
* [x] Increases productivity
* [x] Reduces the development time and run application independently



### Prerequisites
Your system need to have the following minimum requirements to create a Spring Boot application −

* [x] Java 7
* [x] Maven 3.2
* [x] Gradle 2.5



* [x] The entry point of the spring boot application is the class contains `@SpringBootApplication` annotation and the main method

* [x] `@SpringBootApplication` annotation includes Auto- Configuration, Component Scan, and Spring Boot Configuration.



### Spring Initializer
One of the ways to Bootstrapping a Spring Boot application is by using Spring Initializer. To do this, 

* [x] visit the Spring Initializer web page www.start.spring.io 
* [x] choose your Build, Spring Boot Version and platform
* [x] provide a Group, Artifact and required dependencies to run the application.
* [x] click Generate Project button. The zip file will download and the files will be extracted.



### Building RESTful Web Service With Spring Boot
Spring Boot provides a very good support to building RESTful Web Services for enterprise applications

For building a RESTful Web Services, you need to add the Spring Boot Starter Web dependency into the build configuration file.

For Maven user, add the below dependency in your pom.xml file

```java
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>    
    </dependency>
```