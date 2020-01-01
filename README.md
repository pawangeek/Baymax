# Documentation

## Domain : Artificial Intelligence

### Problem Statement
Many under privilaged people in India don't have access to proper healthcare. People dont visit doctors for menial symptoms. Further google search provides drastic results.

### Soultion Statement
Baymax, a healthcare assistant will provide first hand prognosis for symptoms. By no way its a replacement for doctors but its a quick handy and free way for correct detection.

### Overview
This Flask application contains the personal healthcare companion.

### Motivation
After watching movie Big Hero6, I was convinced that I should learn how to create a companion like that.

### How to Run

In the top-level directory:
* Fork this repository
* Install dependancies from Baymax/requirements.txt
* Follwed by `export FLASK_APP=index.py`
* And then flask run
* It Opens a server at your localhost at port 5000

### Key Python Modules Used

* Flask: micro-framework for web application development
* Jinga2 - templating engine
* SQLite - ORM (Object Relational Mapper)
* Flask-WTF - simplifies forms

### How to use Baymax

* On the Startup page click on ‘Next’ to get started.
* Choose your Gender.
* Set your Age using the slider.
* Now you can do one of the following-
* Search for the symptoms you’re suffering from(in the search bar) 
* Click on areas on the figure for selecting symptoms from the pop up menu. Click on Add.
* Answer some additional questions about other symptoms(Yes/No/Don’t Know). 
* You will then see the results. Probabilities of different disease will be displayed. You can further click on diseases to get information on them.


This application is written using Python 3.6.

### Screenshots

![Initial page](/Images/e1.png)
![Gender selection](/Images/e2.png)
![Symptoms Selection 1](/Images/e3.png)
![Symptoms Selection 2](/Images/e4.png)
![Related Diseases](/Images/e5.png)
