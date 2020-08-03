# Building-a-Database-from-scratch
A step by step process of redesigning Aras' database model with MySQLWorkbench.
*Note: This is a project completed on behalf of Aras Corparation as part of a final project for my Database Management class. Dummy data was used through out the process

![Screen Shot 2020-08-03 at 5 23 14 PM](https://user-images.githubusercontent.com/47016027/89228750-2fba8480-d5ae-11ea-80c8-2b29ccf1b47c.png)
# Introduction
A database is an organized collection of data, generally stored and accessed electronically from a computer system. 
Aras’ customers are very big companies like Microsoft and GE Aviation. Each of these large corporations have slightly smaller companies within them. The purpose of this project is to find a way to roll up all of these individual companies that belong to a bigger company under that Enterprise company's accounts.
# Business Rules
one of the first steps in a database design is identifying the business rules. A business rule defines or constrains some aspect of business and always resolves to either true or false. You base a business rule on the way the organization perceives and uses its data, which you determine from the manner in which the organization functions or conducts its business. See below an example of some business rules followed in this project

![Screen Shot 2020-08-03 at 5 40 13 PM](https://user-images.githubusercontent.com/47016027/89230039-993b9280-d5b0-11ea-9d00-e6e657530028.png)
# Entity Relationship Diagram
An ER diagram shows the relationship among entity sets. An entity set is a group of similar entities and these entities can have attributes. An entity in a dbms is a table or attribute of a table. Relationships could be one to one, one to many, or many to many. ER diagrams are used to sketch out the design of a database.

![image](https://user-images.githubusercontent.com/47016027/89231235-e882c280-d5b2-11ea-85c4-239b21dfc57a.png)
#  Relational Schema
Relational schema refers to the meta-data that describes the structure of data within a certain domain. It is the blueprint of a database that outlines the way its structure organizes data into tables.

![image](https://user-images.githubusercontent.com/47016027/89231390-3c8da700-d5b3-11ea-988f-41c7a9be6272.png)
# Create Table
Below are sample queries for creating a table using mysqlworkbench. *Note: Tables can also be automatically uploaded on mysqlworkbench

![image](https://user-images.githubusercontent.com/47016027/89232789-3d740800-d5b6-11ea-8dc5-49a06b7ab352.png)
# Inserting values into table
![image](https://user-images.githubusercontent.com/47016027/89231893-4663da00-d5b4-11ea-923b-b62fbd0daaa9.png)
# Sample Query
![Screen Shot 2020-08-03 at 6 17 27 PM](https://user-images.githubusercontent.com/47016027/89232552-a8710f00-d5b5-11ea-92c3-7a06bedfb6e6.png)

Refrences:
https://www.oreilly.com/library/view/database-design-for/0201752840/ch11s02.html

https://byte-notes.com/relational-schema/#:~:text=Relational%20schema%20refers%20to%20the,structure%20organizes%20data%20into%20tables.
