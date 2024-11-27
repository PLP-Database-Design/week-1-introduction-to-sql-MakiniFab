# SQL Assignment Week 1


## *What You'll Need*
- A computer with internet access.
- A code editor (e.g., Visual Studio Code).
- MySQL Workbench or another SQL database environment.

---



## *Submission Instructions*
1. Answer every question below and put your responses in a file named `answers.md`
2. Push your completed `answers.md` file to your GitHub repository.
3. Submit the GitHub link for review.

---

## **Assignment Questions**

1. State and Explain the components of a DBMS(Database Management System)
The database engine is the core, responsible for storing, retrieving, and updating data, as well as executing queries. The database schema defines the structure of the data, including tables, relationships, and constraints. The query processor interprets and executes SQL queries, optimizing them for performance. Transaction management ensures reliable and consistent processing of data changes, maintaining ACID properties. The storage manager handles physical data storage, indexing, and memory management. The DDL and DML compilers process the schema definitions and data manipulation commands respectively, allowing for database modification and data retrieval. The DBA interface provides administrators with tools to configure, monitor, and maintain the system, including managing security and performance. Lastly, the security and authorization system controls user access to the database, ensuring that only authorized users can interact with the data

2. What is a relational database? Give 4 examples.
A relational database is a type of database that stores data in tables, which are organized into rows and columns. Each table, also known as a relation, represents an entity (such as customers, orders, or products), and the rows in the table represent individual records. The columns represent attributes or properties of the entities.
Example are:
MySQL, a widely-used open-source DBMS; 
Oracle Database, known for its scalability and robustness in enterprise applications; 
Microsoft SQL Server, a relational database system designed for high-performance applications; 
PostgreSQL, an open-source DBMS that supports advanced features and ACID compliance.

3. State and Explain three classifications of SQL?
Data Definition Language (DDL):
Explanation: DDL is used to define and manage the structure of a database. It includes commands that allow the creation, modification, and deletion of database objects like tables, views, and indexes. DDL does not manipulate data directly but rather deals with the schema or structure of the database.
Examples of DDL commands:
CREATE: Used to create database objects such as tables or views.
ALTER: Used to modify the structure of an existing database object (e.g., adding or deleting columns in a table).
DROP: Used to delete database objects, such as tables or views.

Data Manipulation Language (DML):
Explanation: DML is used for managing data within the database. It allows users to insert, update, delete, and retrieve data from the tables. DML operations are often referred to as "queries" because they directly interact with the data stored in the database.
Examples of DML commands:
SELECT: Retrieves data from one or more tables based on specified conditions.
INSERT: Adds new records into a table.
UPDATE: Modifies existing data in a table.
DELETE: Removes data from a table.

Data Control Language (DCL):
Explanation: DCL is used to control access to data in the database. It includes commands that define permissions and access control for users and roles, ensuring that only authorized individuals can perform certain actions on the database.

4. What is the difference between a Primary Key and a Foreign Key?
A Primary Key is a field or combination of fields in a table that uniquely identifies each record in that table. It ensures that every record within the table is unique and provides a way to quickly reference a specific row.

A Foreign Key, on the other hand, is a field in one table that links to the primary key of another table, establishing a relationship between the two tables. It ensures referential integrity, meaning that each value in the foreign key column must either be NULL or match an existing primary key value from the referenced table.

5. What is an Entity-Relationship Diagram?
 Is a visual representation of the entities within a system and the relationships between them. It is a tool commonly used in database design to illustrate how data entities relate to one another. An ERD helps in conceptualizing the structure of a database by showing entities (objects or things within the system), their attributes (characteristics or properties), and the relationships between them.

6. What are the advantages of relational databases?
Data Integrity: Relational databases enforce strong data integrity through the use of constraints such as primary keys, foreign keys, and unique constraints. These rules ensure that data is consistent, accurate, and free from duplication, which helps maintain the quality of the information stored.

Structured Query Language (SQL): SQL is a powerful, standardized language for managing and querying relational databases. It provides a simple and efficient way to retrieve, update, and manipulate data, making it easier for developers and database administrators to interact with the database.

Scalability: Relational databases can handle large volumes of data and scale as needed. With the proper indexing and optimization, they can support complex queries, making them suitable for applications ranging from small systems to enterprise-level solutions.

Data Relationships: One of the main strengths of relational databases is their ability to handle relationships between different data entities through foreign keys. This capability allows for a normalized design that minimizes data redundancy and ensures that data is logically organized in separate tables, making it easier to maintain.

Security: Relational databases come with robust security features, allowing administrators to control access to data by setting permissions on tables, views, and other database objects. This ensures that sensitive data can only be accessed by authorized users.

Backup and Recovery: Relational databases typically offer strong backup and recovery mechanisms. This ensures that data can be restored in the event of failure, minimizing data loss and ensuring continuity of business operations.

7. State four types of data type used to store data in tables?
Integer:
Used to store whole numbers (positive or negative) without decimal points. Commonly used for fields such as IDs, quantities, and age.

VARCHAR:
Used to store variable-length strings of text. VARCHAR allows for more flexibility as it only uses as much storage as needed, whereas CHAR stores fixed-length strings.

Date and Time:
Used to store date and time values. DATE stores only the date, TIME stores only the time, and DATETIME stores both date and time.

Decimal/Float:
Used to store numeric values with decimal points. DECIMAL is used for precise fixed-point numbers, while FLOAT is used for approximate numbers.
   
8. What is the purpose of a database management system (DBMS)?  
The purpose of a Database Management System (DBMS) is to provide a structured and efficient way to store, manage, and retrieve data within a database. It acts as an intermediary between the users and the physical data storage, ensuring that data is organized, accessible, and secure.

*How to edit a [markdownfile](https://www.markdownguide.org/basic-syntax/#headings)*

###  NOTE: You should not fork the repository
