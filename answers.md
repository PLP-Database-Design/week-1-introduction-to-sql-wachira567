Components of a DBMS (Database Management System)
A Database Management System (DBMS) consists of several components that work together to manage data efficiently. The main components include:

Database Engine: The core service for accessing and processing data. It manages data storage, retrieval, and updates.

Database Schema: Defines the structure of the database, including tables, fields, relationships, views, indexes, and constraints.

Query Processor: Interprets and executes SQL queries. It optimizes query performance and translates SQL into a form that the database engine can understand.

Transaction Management: Ensures that database transactions are processed reliably and adhere to ACID properties (Atomicity, Consistency, Isolation, Durability).

Data Dictionary: A metadata repository that stores information about the database structure, including definitions of tables, fields, data types, and constraints.

User Interface: Provides tools for users to interact with the database. This can include command-line interfaces, graphical user interfaces (GUIs), and application programming interfaces (APIs).

Security Management: Controls access to data through user authentication and authorization, ensuring that only authorized users can perform specific operations.

What is a Relational Database?
A relational database is a type of database that stores data in structured tables (relations), where each table consists of rows and columns. Each row represents a record, and each column represents an attribute of the record. Relational databases use Structured Query Language (SQL) for defining and manipulating data.

Examples of Relational Databases:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
Three Classifications of SQL
SQL can be classified into three main categories:

Data Query Language (DQL): Used to query and retrieve data from the database. The primary command is SELECT.

Data Definition Language (DDL): Used to define and manage database structures. Commands include CREATE, ALTER, and DROP.

Data Manipulation Language (DML): Used to manipulate data within the database. Commands include INSERT, UPDATE, and DELETE.

Difference Between a Primary Key and a Foreign Key
Primary Key: A primary key is a unique identifier for each record in a table. It ensures that no two records can have the same value for the primary key column(s) and cannot be NULL. For example, in a Users table, the User ID could serve as the primary key.

Foreign Key: A foreign key is a field (or a set of fields) in one table that uniquely identifies a row of another table. It establishes a relationship between the two tables. For example, in an Orders table, a User ID foreign key could reference the User ID primary key in the Users table.

What is an Entity-Relationship Diagram (ERD)?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities (tables) in a database and the relationships between them. It uses symbols to represent entities, attributes, and relationships, helping to design and understand the database structure. ERDs are essential in the database design phase.

Advantages of Relational Databases
Data Integrity: Relational databases enforce data integrity through constraints (e.g., primary keys, foreign keys) and normalization.

Structured Data: Data is organized in a structured format (tables), making it easy to query and manipulate.

Flexibility: They support complex queries and allow for easy data retrieval and manipulation using SQL.

Scalability: Relational databases can handle large amounts of data and can be scaled vertically (adding more resources to a single server) or horizontally (adding more servers).

Four Types of Data Types Used to Store Data in Tables
Integer: Used to store whole numbers (e.g., INT, BIGINT).

Float/Decimal: Used to store numbers with decimal points (e.g., FLOAT, DECIMAL).

String: Used to store text (e.g., VARCHAR, CHAR, TEXT).

Date/Time: Used to store date and time values (e.g., DATE, TIMESTAMP).

Purpose of a Database Management System (DBMS)
The primary purpose of a Database Management System (DBMS) is to provide a systematic and efficient way to store, retrieve, and manage data. Key purposes include:

Data Storage: To provide a structured environment for storing large volumes of data.
Data Retrieval: To facilitate easy and efficient querying and retrieval of data.
Data Integrity: To ensure the accuracy and consistency of data through constraints and rules.
Data Security: To protect data from unauthorized
