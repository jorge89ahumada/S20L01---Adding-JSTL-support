CRUD excercise example
- Connects to a database and retrieves user data using JSLT and JSP files.
To install the database please run the following command:

CREATE SCHEMA `studyeasy_db` ;

CREATE TABLE `users` (
  `users_id` int NOT NULL AUTO_INCREMENT,
  `username` varchar(45) NOT NULL,
  `email` varchar(45) NOT NULL,
  PRIMARY KEY (`users_id`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

insert into users (username,email) values ("Laura", "laura@mail.com");
insert into users (username,email) values ("Jorge", "jorge@mail.com");
insert into users (username,email) values ("John", "john@mail.com");


