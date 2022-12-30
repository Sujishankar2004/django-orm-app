# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here
![Screenshot (15)](https://user-images.githubusercontent.com/119643785/209985811-178423bc-7e33-4749-a266-09deb79fb9ac.png)

## DESIGN STEPS

### STEP 1:
clone the repository to theia id.start a new app inside the project folder
### STEP 2:
type the oppropriate code for your table and provide appropriate data type to the columns
### STEP 3:
creat a report about your projectb in readme .md file and upload the django.orm.app folder to your remote reporsitory.
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
![Screenshot (13)](https://user-images.githubusercontent.com/119643785/209985651-385990ab-54e1-45df-9288-6513a7db58ed.png)


Include the screenshot of your admin page.


## RESULT
Success.
