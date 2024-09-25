# Ex03 Django ORM Web Application
## Date: 25.09.2024

## AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
<<<<<<< HEAD
```
admin.py 
from django.contrib import admin
from .models import Bank,Loandetails
admin.site.register(Bank,Loandetails)

models.py 
from django.db import models
from django.contrib import admin
class Bank(models.Model):
    customer_id = models.IntegerField(primary_key=True)
    customer_name = models.CharField(max_length=50)
    account_type = models.CharField(max_length=50)
    loan_amount = models.DecimalField(max_digits=10, decimal_places=2)  
    monthly_interest = models.DecimalField(max_digits=5, decimal_places=2)  
    due_date = models.DateField()
=======

>>>>>>> cd20404e88c7234b96d3c29eb8302334ff268773


<<<<<<< HEAD

```
=======
>>>>>>> cd20404e88c7234b96d3c29eb8302334ff268773
## OUTPUT
![alt text](<Screenshot (471).png>)

<<<<<<< HEAD
=======

>>>>>>> cd20404e88c7234b96d3c29eb8302334ff268773

Thus the program for creating a database using ORM hass been executed successfully
