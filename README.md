--By Sugeng Riyanto--
This is registration and login system using getboostrap and Flask Pyhton
Source: https://getbootstrap.com/docs/5.3/getting-started/introduction/
Detail requirement, visit this google site:https://sites.google.com/view/coding9/python-flask/python-with-flask

First, in Visual Studio Code, click menu view==>Command Pallete, choose Create Environment. Then repeat and choose Select Interpreter

Second, install Flask package, click Terminal, then copy the following and right click, to paste:
pip install flask

Third, do the same way like second step to install Flask-MySQLdb
pip install flask-mysqldb

Fourth, Creating Database in SQL(create database):
CREATE DATABASE `db_sample`; 

then, in SQL, copy this to create the table:
CREATE TABLE  `db_sample`.`users` (
  `UID` int(11) NOT NULL AUTO_INCREMENT,
  `UNAME` varchar(50) NOT NULL,
  `EMAIL` varchar(50) NOT NULL,
  `UPASS` varchar(50) NOT NULL,
  PRIMARY KEY (`UID`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;

Fifth, run and debug

sixth, Go to Terminal then deploy the python:
python app.py

That's it! To be Continuous...


