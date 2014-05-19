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

Previous Experience
-------------------

1. What was the most challenging, yet recent, project you worked on?
2. What languages/technologies did you use for development/production?
   1. PHP - Vanilla, Yii, Symfony2, Zend, CodeIgniter, other
   2. Javascript - Vanilla, AngularJS, EmberJS, Knockout, Backbone, other
   3. RDBMS - MySQL, SQL Server, Oracle, other
   4. Web Server - Apache, nGinx, other
   5. NoSQL - Memcache, Redis, Mongodb, Couchdb, other
   6. OS - Windows, Linux
4. What were your daily tasks?

### Planning and Management

1. What was the standard development flow/process?
   1. Analysis
   2. Design
   3. Implementation
   4. Testing
   5. Deployment
   6. Other

2. Who provided specifications to the team?
   1. Developers
   2. Project manager
   3. Analyst
   4. Product manager
   5. Other
   
3. Who tracked the progress of the projects you were working on?
   1. Nobody
   2. Client
   3. Project manager
   4. Product manager
   5. Lead developer
   6. Other
   
4. What issue tracking system?
   1. None
   2. JIRA
   3. Trac
   4. Other

### Code Development

1. How big was the code-base?

   1. Small (a few SLOC)
   2. Medium (a few thousand SLOC)
   3. Large (many thousands SLOC)
   4. Other

2. How did you manage/partition the code-base?

   1. Per subsystem/package
   2. Per class
   3. Other

3. What IDE did you use?
   1. Netbeans
   2. Eclipse
   3. VIM
   4. Other
   
4. How did you share code?
   1. Emails
   2. FTP
   3. Subversion
   4. GIT
   5. Other

5. How did you handle source code conflicts with other team members?
   1. VCS Branching
   2. Codebase partitioning
   3. Other

6. How did you manage the team's different configurations?
   1. Repository with configurations
   2. Unversioned configuration files
   3. Other


8. Did you write/maintain code documentation?
   1. Word
   2. Wiki

9. How did you produce documentation from your source code?

### Database Development

1. How large was the database schema you were handling?
   1. Small (a few tables)
   2. Medium (a few tens of tables)
   3. Large (tens of tables)
   4. Other
   
2. Did you participate in the design of the schema?
   1. Yes
   2. No
   3. Other

2. How did you version database schema/data changes?
   1. We did not
   2. Database utility
   3. Framework/library
   4. Other

3. How did you document the database schema?
   1. Table and column comments
   2. Separate data dictionaries
   3. ERD models
   4. Other

Testing
-------

1. Did you have a QA process?
   1. Yes
   2. No
   3. Other

2. Who wrote test cases?
   1. Analyst
   2. Product Manager
   3. Lead Tester
   4. Client
   5. Other

3. Did you write unit tests?
   1. Yes
   2. No
   3. Other

Performance
-----------
1. What was the biggest traffic your software had to handle?

2. What optimizations have you utilized?

3. What scalability paths have you used?
   
Deployment
----------

1. How did you deploy code?
   1. FTP
   2. Subversion
   3. GIT
   4. Other

2. Had you adopted a versioning schema?
   1. Yes
   2. No
   3. Other

3. How did you deploy database schema changes?
   1. Manually
   2. Automated migrations
   3. Other



Data Modeling – Databases
-------------------------

1. How do you model a 1-to-1 relation in a Relational Database?
2. How do you model a 1-to-many relation in a Relational Database?
3. How do you model a many-to-many relation in a Relational Database?
4. What is a primary key?
5. Can you define a multi-column primary key?
6. What is a foreign key?
7. What's the difference between varchar and text?

Transactions & Concurrency – Databases
--------------------------------------

1. What is Atomicity/Consistency/Isolation/Durability in ACID?
2. Give an example of transaction usage
3. What is a deadlock?
4. What is an aggregate query?
5. What is the difference between a LEFT OUTER JOIN and an INNER JOIN?
6. What is a standard alternative to most subqueries?
7. Are INDEXes always a good idea?


Object-Relational Mapping
-------------------------

1. What is ActiveRecord?
2. What is lazy and eager loading? What is their difference?



Software Engineering Principles and Paradigms
---------------------------------------------

1. What is Objected Oriented programming? Name a few languages supporting OOP.
2. What is Functional Programming? Name a few languages supporting FP.
3. What is Refactoring?
4. What is Coupling?
5. What is Encapsulation/Abstraction/Inheritance/Polymorphism in OOP?

Software Engineering Design and Enterprise Patterns
-----------------------------------------------

1. What is the Singleton pattern?
2. What is the Observer pattern?
3. What is the Adapter pattern?
4. What is the Factory method pattern?
5. What is the MVC pattern?
6. What is a Service Layer?
7. What is a Data Transfer Object?

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
10. What is the difference between a static and a non-static method in PHP?

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


HTTP
----

1. What is the difference between POST and PUT?
2. Can you have a request body in GET requests?
3. How are cookies represented in HTTP messages?
3. Why would you need a Web API?
4. What is the difference between a RESTful and an RPC-style web API?


References
----------

1. [Google Search for "PHP Developer Interview Questions"](https://www.google.gr/search?q=php+developer+interview+questions&oq=php+developer+interview+questions)



