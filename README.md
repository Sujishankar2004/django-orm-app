# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

### STEP 2:

### STEP 3:

Write your own steps

## PROGRAM

Include your code here
```
from django.db import models
from django.contrib import admin

# Create your models here.

class Employee (models.Model): 
    Name=models.CharField(max_length=100)
    Age=models.IntegerField()
    Phonenumber=models.CharField(max_length=11,help_text="Phonenumber")
    email=models.EmailField()

class EmployeeAdmin(admin.ModelAdmin):
    list_display=('Name','Age','Phonenumber','email')
```

## OUTPUT
![emloy](./image/Screenshot(13).png)

Include the screenshot of your admin page.


## RESULT
