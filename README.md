# libraryManagement
Python based library management system using TKinter
Program is executed using Pycharm IDE
Installation required:
1. pip install tkinter
2. pip install pillow
3. Please install MySQL server using the root password as "mypass".

Then create a database with the following tables.
***************************************************************************************************
create database db2;           (enter)

use db2;           (enter)

create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));           (enter)

create table books_issued(bid varchar(20) primary key, issuedto varchar(30));           (enter)
*********************************************************************************************************
Then run the main.py 

Note:
complete code and working was followed from the link----> https://data-flair.training/blogs/library-management-system-python-project/
