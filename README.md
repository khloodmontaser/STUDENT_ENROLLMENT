# STUDENT_ENROLLMENT
### developing a student enrollment database with a user-friendly GUI using python

> The objective of this project is to develop a comprehensive student enrollment database with a user-friendly graphical user interface (GUI)
that can store and manage student data efficiently.
The database will be designed to streamline the process of student enrollment and enable educational institutions to easily manage
student records.
a GUI will be developed with driving code that enables users to select and update the database with new student records. Additionally, the
database will be hosted on a free server, which will allow users to access it from anywhere in the world.

------

### Problem statemen

> our project is to Develop a comprehensive student enrollment database project and create a user-friendly GUI with a suitable frontend language such as Python, A comprehensive student enrollment database is necessary to centralize management, improve accuracy, streamline processes, and enable data analysis for educational institutions.


### Technical details

> FRONTEND FRAMEWORK: ``TKINTER``
HOSTING: ``FREEMYSQL HOSTING``


### GUI FEATURES

> there're 6 buttons that represents the instructions that we can do on our database like adding new records, updating, etc.
the database table have 5 columns to represent the student ID, first name, last name, address and phone number.
The table displays a history of all the records. The GUI is user-friendly and providesan easy way to manage the database

![image](https://user-images.githubusercontent.com/113125527/236682261-27e32708-4d44-4375-a094-1e7fbdeab025.png)

### DATABASE DESIGN

> we designed our database using: ``MySQL workbench``

it's a popular tool for designing and managing MySQL databases. It offers a wide range of features for creating and modifying database schemas, as well as managing data, users, and security.

MySQL Workbench provides a visual interface for designing and creating database schemas. Users can create tables, define relationships between tables, and generate SQL code to create the database
MySQL Workbench includes a SQL editor that allows users to write and execute SQL queries against their databases.
MySQL Workbench allows multiple users to work on the same database simultaneously.

![image](https://user-images.githubusercontent.com/113125527/236682358-b6a6cb29-4ee3-4b9b-9430-a9e7c4eaf88f.png)

### ERROR HANDLING

```
To make sure that there is no empty field that'll cause any error we implemented the "Not null" constraint to ensure that we have all the data about each student By setting a field to "Not null", the database will reject any attempts to insert a record that has a null value in that field. so if a user tries to insert a student record with a missing field, the database will return an error message indicating that the required field is missing.

and if a user tries to search a student that's not in the database, the database will return an error message indicating that No data found

if a user tries to update a field without selecting it first, an error message will pop in the screen "please selected a data row" because it can perform any operation without a selected field
```

### WARNING MESSAGES

ask the user if he wants to delete what he has selected or if he wants to delete all data before deleting them.
```
to prevent accidental data loss and give users the opportunity to double-check their actions before making irreversible changes to the data
```


