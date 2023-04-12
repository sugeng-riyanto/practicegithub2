--By Sugeng Riyanto--
# This is registration and login system using getboostrap and Flask Pyhton
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
Right-click (CTRL+CLICK) http://127.0.0.1:5000 then open your browser.

sixth, Go to Terminal then deploy the python:
python app.py

# How to push the repository in GitHub
Create folder in your github account, then select this statement such us git remote add origin https://github.com/sugeng-riyanto/coba-gitignore.git 
Initialization
git init
git add README.md

push
git remote add origin https://github.com/sugeng-riyanto/coba-gitignor.git 

check status
git status

add all files
git add .

check the update status
git status

Ready to commit
git commit -m "first commit"

Ready to push
git push -u origin main

if you want to name the branch master. Run:
git push -u origin master #instead of git push -u origin main

if you want to name the branch main. Run:
git checkout -B main before git push -u origin main

clear the gitbash
clear

In the folder project, add file with the name is .gitignore
example, we can specify ignore file(s) not include to repo such us config.txt, data/, *.exe
Suggestion: https://github.com/github/gitignore
https://www.toptal.com/developers/gitignore/ or https://gitignore.io/

Second push
git add .
git status
git commit -m "second commit"
git push

git branch -M main

That's it! To be Continuous...
