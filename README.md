# Building-a-Database-from-scratch
A step by step process of redesigning Aras' database model with MySQLWorkbench.
![Screen Shot 2020-08-03 at 5 23 14 PM](https://user-images.githubusercontent.com/47016027/89228750-2fba8480-d5ae-11ea-80c8-2b29ccf1b47c.png)
# Introduction
A database is an organized collection of data, generally stored and accessed electronically from a computer system. 
Aras’ customers are very big companies like Microsoft and GE Aviation. Each of these large corporations have slightly smaller companies within them. The purpose of this project is to find a way to roll up all of these individual companies that belong to a bigger company under that Enterprise company's accounts.
# Business Rules
one of the first steps in a database design is identifying the business rules. A business rule defines or constrains some aspect of business and always resolves to either true or false. You base a business rule on the way the organization perceives and uses its data, which you determine from the manner in which the organization functions or conducts its business. See below an example of some business rules followed in this project

![Screen Shot 2020-08-03 at 5 40 13 PM](https://user-images.githubusercontent.com/47016027/89230039-993b9280-d5b0-11ea-9d00-e6e657530028.png)
# Entity Relationship Diagram
An ER diagram shows the relationship among entity sets. An entity set is a group of similar entities and these entities can have attributes. An entity in a dbms is a table or attribute of a table. Relationships could be one to one, one to many, or many to many. ER diagrams are used to sketch out the design of a database.
