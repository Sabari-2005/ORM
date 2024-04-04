# Ex02 Django ORM Web Application
## Date: 
04.04.2024
## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).


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

models.py

from django.db import models

class Student(models.Model):
    stdid=models.IntegerField()
    stdname=models.CharField(max_length=30)
    dept=models.CharField(max_length=20)
    cgpa=models.FloatField()
    aadhar=models.BigIntegerField(null=True)

admin.py

from django.contrib import admin

from .models import Student
admin.site.register(Student)

## OUTPUT
![output](https://github.com/Sabari-2005/ORM/assets/139338709/4f5e9a17-f783-46c9-bc46-9d91b9b4d8ed)




## RESULT
Thus the program for creating a database using ORM hass been executed successfully
