Goals
-----

1. Development - Code-base scalability: Managing growing code-bases → writing modular code, promoting loose coupling, using standard software patterns
2. Development - Code-base re-usability: Making software components re-usable → writing modular code, writing documentation
3. Development - Code-base maintainability: Making code maintainable and revieable → Using standard coding conventions, writing documentation
4. Development - Team-size scalability: Working in large teams → Using version control systems, utilizing branching strategies
5. Development - Interoperability: Making systems that easily interoperate with others → Using industry standards
6. Modern technologies: Staying up-to date
7. Runtime - Load scalability: Performance-wise scalable systems → Determining appropriate architectures, utilizing caches/databases/algorithms

Key areas
---------

1. Data Modeling (ERD)
2. Data Manipulation (SQL)
3. Object-Oriented Software Engineering (UML)
4. Programming Language (PHP)
5. Programming Framework (Yii)
6. Application Interfaces (HTTP)
7. Testing

Data Modeling – Databases
-------------------------

1. How do you model a 1-to-1 relation in a Relational Database?
2. How do you model a 1-to-many relation in a Relational Database?
3. How do you model a many-to-many relation in a Relational Database?
4. Can you define a multi-column primary key?

Transactions & Concurrency – Databases
--------------------------------------

1. What is Atomicity in ACID?
2. What is Consistency in ACID?
3. What is Isolation in ACID?
4. What is Durability in ACID?
5. Give an example of transaction usage
6. What is a deadlock?
7. What is an aggregate query?
8. What is the difference between a LEFT OUTER JOIN and an INNER JOIN?
9. What is a standard alternative to most subqueries?
10. Are INDEXes always a good idea?


Database Maintenance
--------------------

1. How do you version database schema/data changes?


Object-Relational Mapping
-------------------------

1. What is ActiveRecord?
2. What is lazy and eager loading? What is their difference?



Object-Oriented Software Engineering
------------------------------------

1. What is Refactoring?
2. What is Coupling?

Object-Oriented Software Engineering - Patterns
-----------------------------------------------

1. What is the Singleton pattern?
2. What is the Observer pattern?
3. What is the Adapter pattern?
4. What is the MVC pattern?
5. What is a Service Layer?
6. What is a Data Transfer Object?

Programming Language – PHP
--------------------------

1. What is the difference between an interface and an abstract class?
2. What is a trait?
3. What is an iterator?
4. What is a namespace?
5. What is an auto-loader?
6. What are PHP reflections?
7. When do you use the “global” keyword?
8. What is the difference between htmlentities, urlencode, serialize and json_encode?
9. Have you ever used cURL?

UML
---

1. What is UML?
2. What UML diagram would you use for the following?

   “The client sends a request to the Webserver. The Webserver makes a query to the database. After receiving the database response, the Webserver processes the results. Finally, the Webserver responds to the client”
3. What UML diagram would you use for the following?

   “First you initialize the sum variable to zero. Then you loop through all elements of the input array. For each element, you add the element's price to the sum variable. At the end, you print the sum variable.”
4. What UML diagram would you use for the following?

   “When a payment transaction is created, it's said to be in “CREATED” state. From this state, it can either be accepted or rejected by the administrator. If it's accepted, its state becomes “ACCEPTED”, otherwise it becomes “REJECTED”.”
5. What UML diagram would you use for the following?

   “The system will consist of a MySQL database which is connected to an Apache Webserver, running our PHP Web Service. The PHP Web Service is then accessible from the HTML5 Web Application and the Mobile Applications over HTTPS”

Yii Framework
-------------

1. What are scopes in ActiveRecord?
2. Have you ever used CEvents?
3. Have you ever used CBehaviors?
4. Have you ever built a CApplicationComponent?
5. What does CComponent offer?


Working with a team
-------------------

1. How do you develop and test code when working with a team?
2. How do you manage the team's different configurations?
3. How do you avoid source code conflicts with other team members?
4. How do you reduce the need for “how does this class you built” questions between team members?


HTTP
----

1. What is the difference between POST and PUT?
2. Can you have a request body in GET requests?
3. Why would you need a Web API?
4. What is the difference between a RESTful and an RPC-style web API?

Documentation
-------------

1. How dow you produce documentation from your source code?
