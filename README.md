MGNREGA python project
===============

Introduction
----
This is the python project with sqlite compatibility.


### Project Document

Project documentation link : [Documentation file](https://docs.google.com/document/d/13SEqYxdvtYwUFO-XHNDG9_7hXKbOunJDsURZevZUAis/edit?ts=5e2546f9)


### Database File
Database file is present at location 'mgnrega/venv/src' with name as 'database.db'


### Different Roles in project 

**BDO(Block Development Officer):** This role is like Admin, where admin can perform CRUD operation for GPM and 
Projects. Admin can also approve work allotment and wage allotment requests for members/Labours made by GPM who are 
associated with the logged in Admin. Admin can also see the complaints filed by members/Labours.

**GPM(Gram Panchayat Member):** This role is like sub-admin, where GPM can perform CRUD operations for members/labours,
issue job card, allot project to members and see complaints filed by the members associated with that GPM. GPM can also
see the list of projects allotted to each member with their status (APPROVED/REJECT/PENDING).

**Members:** This role is for Labours, where they can see their details and wage they get. They can also file 
complaint/feedback to GPM and BDO and can see all the complaint(s) filed by the member itself.


Login credentials for BDO
---
```   
email: abhradeb@gmail.com
password: abhradeb

```

Setup for Running the Project
---
```   
1. Open the project MGNREGA
2. Move to src folder
    -> cd venv/src
3. Run pythonn file 'run.py'
    -> python run.py

```
```

```
