# OOP-Final-ProjectFINAL PROJECT
OBJECT ORIENTED PROGRAMMING

BANK STIMULATION


SUBMITTED BY
 
 
[Mujtaba Ahmed]
SP20-BSE-079

 
 
GITHUB LINK



https://github.com/Mujtaba-cpu/OOP-Final-Project.git




INTRODUCTION

Our stimulates a bank's working on 2 entities i.e.

-ACCOUNTS-
-EMPLOYEES-
They both have following in common:
•	Personal details
1.	Name
2.	Phone Number
3.	Address

For which we used a base class "Person" and derived 2 classes from it.
An account has the following attributes:
    -Account Number
    -Balance

An Employee has the following attributes:
    -Employee Id
    -Designation
    -Salary

Then we have 2 classes
    -AccountList
    -EmployeeList

Which are used to store data regarding both entities, 
AccountList works out different tasks performed on an Account and interreacts with a file named “Accounts”
EmployeeList works out different tasks performed on an Employee and interreacts with a file named “Employee List”

It implements following OOP Concepts
-Classes
-Inheritance
-Encapsulation
-Polymorphism
-Interface
-Array List
-Exceptions
-File Handling
STARTUP INTERFACE
This basically asks you to choose on whom to want to work on
 
CUSTOMER INTERFACE-FILE BEFORE ANY CHANGES
This is the interface when you choose option 1
 

ENTER NEW ACCOUNT
This adds a new account to the existing file 
 

  

SEARCH ACCOUNT
It uses Account Number to find the Account from the file and then returns an object of type Account
 
UPDATE ACCOUNT
This takes updated details as input and then updates the object and file
 

DELETE ACCOUNT
Uses an account number to delete that specific account
	 
WITHDRAW MONEY
Takes Account number and money as input, then deducts the specified amount from the relative account’s balance
 

DEPOSIT MONEY
Takes Account number and money as input, then adds the specified amount to the relative account’s balance
 





TRANSFER MONEY
Takes sender Account number, receiver Account number and money as input, then deducts the specified amount from the senders account’s balance and adds it to the receiver’s account balance.
 

DISPLAY
Display all objects in file
 
EMPLOYEE INTERFACE-FILE BEFORE ANY CHANGES
 


ADD, SEARCH, UPDATE AND DELETE 
These functions are same as above with minor changes i.e.
Instead of acc number employee id is used, and these functions interacts with employee class and file “Employee List”
INCREMENT SALARY
This takes employee id and the increment percentage as input and the increments the salary of the relative employee by the given percentage.
	 

