https://docs.google.com/document/d/1ZvriCsOPb3RXobv1UM_sgmvcb70kGVIOdINROdjOEro/edit#


Create emulator processing and web interface for it
Test

Overall objective:
Create a system of processing of cash (as a bank)
There are constantly updated data on the movement of funds contained in a database
the system must process the data and make transactions
Technologies:
Database - MySQL or PostgreSQL. The database structure is left to the discretion of the Executive job.
The system should be a web application written in Java 7-8, deployed using Tomcat 7
To create a test is possible to use JMeter
To develop recommend using IntelliJ Idea

System Requirements:
It must be able to perform the following operations via the web interface:
Manage bank accounts:
add / delete bank accounts (user accounts)
get a list of all existing bank accounts
receive the balance in the specified bank account
Manage cash:
deducted from the balance of the said amount from the specified bank account
Adds the specified amount to the designated bank account
transfer a specified amount from one bank account to another
The system must prohibit the appearance of a negative balance in the bank account
The system should ensure consistency of data at all loads
Do not use Optimistic / Pessimistic Locking (and other equipment) means the database
Testing of the system:
It is necessary to create a test plan for stress testing systems
The tests should simulate a situation where more than one hundred members of bank accounts at the same time actively using the capabilities of the system, and check the correctness of the final state of the bank accounts
