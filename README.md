# SQL quizzer
[![SQL Quizzer](/project_SQLquizzer-1000px.jpg)](https://mirnesglamocic.com/sql-quizzer/index.html)
This repository contains a dynamic responsive SQL quizzer made with PHP MySQL, HTML, and CSS. So, quizz contain some questions by w3school where user need to choose correct answer. 

There is also the possibility of adding a question, and after that that question appears with the other questions in the quiz, and is instantly inserted into the database. There are two tables in the database, one for questions and the other for answers, and with the help of the PHP mysqli api, the entered answer is checked. Each answer has the value of one point and after all the questions the total number of points won appears. This is achieved with the help of PHP sessions, which are started during each quiz and are destroyed at the same time so that the number of points is not added up for each quiz.

---

To check how it looks, please click preview.
##
[PREVIEW](https://mirnesglamocic.com/sql-quizzer/index.html)

