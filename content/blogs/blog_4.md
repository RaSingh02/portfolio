---
title: "Database Types"
date: 2022-03-01
draft: false
author: "Randeep Singh"
Description: "This post focuses on the main three different types of databases and the differences between SQL and NoSQL."
---

### Types of Databases

There are three general database types based on the following models:

1. Relational Database
2. Non-Relational Database
3. Object-Oriented Database

We will be taking a look at all three types of databases. The main difference between them is the way information looks inside the database, as such each model has its own management system and data relationships.

#### Relational Database

The relational database is the most used out of the three and is the oldest model. There are three critical components of this database:

1. Tables
2. Rows
3. Columns

Using a query language, most commonly SQL, or Structured Query Language, a relational database provides a set of data rows in response to a query. Relational databases are most commonly used for online transaction systems where support for many users and frequent queries are needed to complete online transactions. They are also used in IoT, the Internet of Things, devices since they are lightweight and have the processing power needed for edge computing. Where the device connects to a network to deliver and receive instructions from a central server, most likely the cloud or a data center. Relational databases are also used in data warehouses where mass storage can be easily integrated and optimized for mass queries from multiple sources.

#### Non-Relational Database (NoSQL)

This type of database stores data differently from relational databases. There are four different types of NoSQL databases types:

1. Document
2. Key-Value
3. Column based
4. Graph

Non-relational databases are known to be flexible as they can easily handle different levels of data easily, from structured to unstructured. They can also scale well with on-demand servers and can provide quick query responses. Due to their real-time data replication, they have limited downtime which is beneficial towards large data centers, such as those that Google has. The scalability of cloud-computing architecture scales beautifully with non-relational databases as well. NoSQL databases are generally used for real-time systems as they provide agile real-time and combine operational and analytical systems into one. They can be customized to fit any users' needs as they have elastic scaling. Since NoSQL has low latency, they are used in financial systems to detect fraud quickly and efficiently.

#### Object Database

This type of database represents data similar to that of objects in an object-oriented programming language. There are four critical components of an object database: 

1. Objects
2. Classes
3. Methods 
4. Pointers

Object databases combine concepts from object-oriented programming with database capabilities. Due to the nature of this database, data is easy to retrieve and save. It also helps with modeling as real-world issues and information are more closely related to objects, making complex tasks easier to model and solve. With user-defined classes, custom and complex data types can be created to fit the users' needs. This database also combines seamlessly with object-oriented programming languages such as Java. Due to ACID compliance, transactions can occur with conflicting changes. These databases are great for high-performance applications where fast data retrieval is necessary. Scientific data calculation and storage are also compatible as complex data can easily be defined and stored to the users' needs.