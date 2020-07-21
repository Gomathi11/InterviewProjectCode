Step 1: Using Mysql database service and created database as "testDatabase"

Step 2: Create employee table syntax

CREATE TABLE `Employee` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(45) NOT NULL,
  `age` int(11) NOT NULL,
  PRIMARY KEY (`id`)
);

Step 3: Created Spring Boot applications with mysql and jpa repositories

Step 4: Configured Database configurations in application.properties file

Step 5: InterviewProjectApplication is the SpringBootApplication class

Step 6: Created Entity employee class for the database table

Step 7: Created employee repository interface for crud operation to the database

Step 8: Created service and controller class for business logic

Step 9: To run the application Click on the project -> Run As -> Spring boot app . App will be running on the port 8090 which is configured in application.properties file



