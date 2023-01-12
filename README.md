# loginpage-using-php
- First create a database (any name for database);
- use the database 
-use the following query to create table:
CREATE TABLE users (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);
....
--------- to run the project---------
* project should be create inside the xampp > htdocs > than create the folder inside the folder add all the php files like, config.php, login.php ......
than use localhost/foldername/filename(login.php)  .. example
