-- CREATE DATABASE ckc_markus;

USE ckc_markus;
/*
CREATE TABLE Pasakumi (
id INT NOT NULL AUTO_INCREMENT PRIMARY KEY ,
date_and_time datetime NOT NULL ,
title VARCHAR(100) NOT NULL ,
venue VARCHAR(100) NOT null 
);
*/

/*

INSERT INTO Pasakumi
(date_and_time, title, venue)
VALUES
("2024-03-31 13:00:00", "Lieldienas Cēsīs", "Rožu laukums"),
("2024-04-04 18:00:00", "Leļļu teātra izrāde 'Gangsteromīte'", "Koncertzāle 'Cēsis'"),
("2004-07-19 08:00:00", "Cēsu pilsētas svētki 818", "Cēsis");

*/
/*
CREATE TABLE kolektivi (
id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
`name` VARCHAR(80) NOT NULL ,
`description` VARCHAR(500)NOT NULL 
);
*/


/*
INSERT INTO  kolektivi 
(`name`, `description`)
VALUES
("Cēsis", "Pūtēju orķestris"),
("Raitais solis", "Tautu deju ansamblis"),
("Vidzeme", "Jauktais koris"),
("Dzieti", "Tautas vērtes kopa");
*/
SELECT * FROM Pasakumi;
SELECT * FROM kolektivi;
