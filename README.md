# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS
### STEP 1: 
fork the repository and then clone it into the theia ide

### STEP 2:
create django project then create app and superuser account

### STEP 3:
make changes in settings and type your design code in models and the code in admin and then run the server.
## STEP 4:
login on admin with superuser account and populate the record.


Write your own steps

## PROGRAM
```
from django.db import models
from django.contrib import admin
# Create your models here.
class vehicle_details(models.Model):
    vehicleno = models.CharField(primary_key = True,max_length=8)
    customername = models.CharField(max_length=100)
    entrytime = models.TimeField()
    exittime = models.TimeField()
    parkingslot = models.CharField(max_length=200)


class vehicle_detailsAdmin(admin.ModelAdmin):
    list_display = ('vehicleno','customername','entrytime','exittime','parkingslot')
```
## OUTPUT

Include the screenshot of your admin page.


## RESULT
the program was executed successfully
