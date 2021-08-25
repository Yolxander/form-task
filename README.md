# form-task

-needs better email validation when registering

Database name is taskdb, sql code to create table is:
"CREATE TABLE users (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50) NOT NULL UNIQUE,
    email VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP
);

This bug (commit dates are mixed up) was caused by my ide when pushing the changes to github.
![ScreenShot](/Screenshot.png)


