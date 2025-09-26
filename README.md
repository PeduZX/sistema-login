CREATE DATABASE backFront;
USE backFront;

CREATE TABLE users (
id INT PRIMARY KEY AUTO_INCREMENT,
nome VARCHAR(100) NOT NULL,
email VARCHAR(100) UNIQUE NOT NULL,
senha VARCHAR(255) NOT NULL
);




DROP DATABASE backFront;
SELECT * FROM users;


<img width="708" height="128" alt="image" src="https://github.com/user-attachments/assets/dcabecf7-c2ef-4b0a-a0c2-055927ac5110" />
