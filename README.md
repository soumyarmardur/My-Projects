# Table of Contents

This Repository contains multiple projects related to Machine Learning,Django and R/Python.

<b>Tools Used:</b> Anaconda3, Microsoft SQL Server, R Studio, PyCharm, Postman

# Table of Contents
1. [Machine Learning](#machine-learning)
2. [Python with Django](#python-with-django)
3. [Python with Sqlite](#python-with-sqlite)
4. [Sample R Scripts](#sample-r-scripts)
5. [Sample Python Scripts](#sample-python-scripts)


## Machine Learning

### Projects
Problem Statement | Description
------------ | -------------
Employee Attrition Prediction | This project is regarding retaining outstanding employees. You can analyze all relevant employee data and develop focused employee retention programs.
Loan Aproval Prediction | This project is regarding automating the loan eligibility process based on customer detail provided using ML.
No Show Appointment Prediction | Content in the second column
No Show Appointment Prediction | Content in the second column

### Feature Engineering
`Outliers`<br>
`Multi Colinear`<br>
`Normalization`<br>
`Regularization`<br>

### Algorithm Used
`Linear Regression`<br>
`Logistic Regression`<br>
`Decision Tree`<br>
`Random Forest`<br>
`Naive Bayes`<br>


## Python with Django

Please find the steps to implement the Django Project

Installation  Steps:
```
* pip install Django
* django-admin startproject project
* python manage.py runserver
* django-admin startapp user
```

Understanding different scripts in Django
```
* URL.py --> URL Configuration script<br>
* form.py --> Form/Attribute creation scripts<br>
* models.py --> script which creates database schemas(class name would be considered as table name)<br>
* views.py --> script which takes in web request and throws web response(logic is written here to save the form and send the respective attributes to DB)<br>
* Settings.py --> script which contains default settings. we can add configurations like custom password validation and "app" name in here<br>
```
Evaluation:
```
* python manage.py runserver<br>
* go to chrome and type http:127.0.0.1/ <br>
* register using your username(details like username, password, confirm password and emails should be entered) <br>
* login using your username(details like username, password should be entered) <br>
* create profile after login(details like firstname, lastname, contactno,email,.... should be entered) <br>
* To generate SQL commands to create the table --> python manage.py makemigrations
* To create the table in database  --> python manage.py migrate
* check the SQLLite DB Browser to view details of user profile
```

## Python with Sqlite
## Sample R Scripts
## Sample Python Scripts
