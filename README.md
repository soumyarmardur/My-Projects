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
* Employee Attrition Prediction
  Description: 
  
* Loan Aproval Prediction
  Description:
  
* No Show Appointment Prediction
  Description:

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

<b>Step5:</b> 
```
Understanding different scripts in Django<br>
`URL.py` --> URL Configuration script<br>
`form.py` --> Form/Attribute creation scripts<br>
`models.py` --> script which creates database schemas(class name would be considered as table name)<br>
`views.py` --> script which takes in web request and throws web response(logic is written here to save the form and send the respective attributes to DB)<br>
`Settings.py` --> script which contains default settings. we can add configurations like custom password validation and "app" name in here<br>
```
<b>Step6:</b> Executing the project
1) python manage.py runserver<br>
2) go to chrome and type http:127.0.0.1/ <br>
3) register using your username(details like username, password, confirm password and emails should be entered) <br>
4) login using your username(details like username, password should be entered) <br>
5) create profile after login(details like firstname, lastname, contactno,email,.... should be entered) <br>

<b>Step7:</b> To generate SQL commands to create the table
python manage.py makemigrations

<b>Step8:</b> To create the table in database
python manage.py migrate

<b>Step9:</b> check the SQLLite DB Browser to view details of user profile



## Python with Sqlite
## Sample R Scripts
## Sample Python Scripts

### Example 1 Heading
* Machine Learning 
* Python with Django
* Python with Sqlite
* Sample R Scripts
* Sample Python Scripts



## 2) Python with Django

The Repository contains models.py,forms.py,view.py and other scripts related to django

