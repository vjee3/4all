List of Software Terms
======================

## 10 popular commands of daily use
1. **sudo** - This SuperUserDo is the most important command Linux newbies will use. Every single command that needs root’s permission, need this sudo command.

2. **cd** - To Change directory

3. **clear** - To clear the terminal screen

4. **touch** - To create file

5. **cp** - To copy file/ folder

6. **mv** - To move/ rename file/ folder

7. **apt-get** - [Advanced Packaging Tool (APT) package manager] - Used to install, remove and upgrade any package we’ve
    > example: $ sudo apt-get update

8. **ls -al** - To see the list of files and folders of the working directory

9. **cat** - To see the file contents

10. **vim** / **code** - To open any file in Vim or Code editor


## 10 popular network commands
1. **ping** - This is used to provide a basic connectivity test between the requesting host and a destination host

2. **ifconfig** - To find out the specific IP configuration of the variously affected hosts

3. **netstat** - To see Active Internet connections

4. **nslookup** - Some of the most common networking issues revolve around issues with Dynamic Name System (DNS) address resolution issues. DNS is used by everyone using the Internet to resolve commonly known domain names (i.e. google.com) to commonly unknown IP addresses (i.e. 74.125.115.147)

5. **route** - This utility is used to display the current status of the routing table on a host

6. **traceroute** - traceroute print the route packets take to network host

7. **dig** - DIG (Domain Information Groper) is a flexible tool for interrogating DNS name servers

8. **w** - It  prints a summary of the current activity on the system, including what each user is doing, and their processes

9. **nmap** - (eg. $ nmap localhost) nmap is a one of the powerful commands, which checks the opened port on the server

10. **scp** - (eg. - scp $filename user@targethost:/$path) scp allows you to secure copy files to and from another host in the network
    

## 10 popular OS commands
1. **mail** - (mail -s "This mailing service is great" -a From:cusat.brdas@gmail.com) To send mail from terminal

2. **ping -c 10 127.0.0.1 &**  - This command will cause the application to ping its loopback network adapter for 10 seconds

3. **xdg-open** - To open image/video/website 
    eg.: 
    > xdg-open http://askubuntu.com/ or xdg-open $filename 

4. **mkdir** - To create directory

5. **rmdir** - To remove directory

6. **locate** - To get the location of given file in entire directories

7. **rm** - To remove file

8. **find** - to locate file if you don't know the exact name of file

9. **users** -  Return the current user name

10. **uptime** - In Linux uptime command shows since how long your system is running and the number of users are currently logged in and also displays load average for 1,5 and 15 minutes intervals


## [Database](https://en.wikipedia.org/wiki/Database)
A database is an organized collection of data, generally stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.

## [SQL Database](https://en.wikipedia.org/wiki/SQL)
SQL is a domain-specific language used in programming and designed for managing data held in a relational database management system, or for stream processing in a relational data stream management system.

## [NoSQL Database](https://searchdatamanagement.techtarget.com/definition/NoSQL-Not-Only-SQL)
NoSQL, which stand for "not only SQL," is an alternative to traditional relational databases in which data is placed in tables and data schema is carefully designed before the database is built. NoSQL databases are especially useful for working with large sets of distributed data.


## [10 popular databases](https://www.softwaretestinghelp.com/database-management-software/)
1. **Oracle RDBMS:** Oracle database is the most widely used object-relational database management software. The latest version of this tool is 12c where c means cloud computing.

It supports multiple Windows, UNIX, and Linux versions.

It is secured, occupies less space, supports large databases, and reduces CPU time to process data.

2. **IBM DB2:** Latest release 11.1.Developed in the year 1983.The language used is Assembly Language, C, C++ for writing it.

It supports multiple Windows, UNIX, and Linux versions.

It is very easy to install and set up and data is easily accessible, we can save the huge amount of data almost up to pet bytes.

3. **Microsoft SQL Server:** Developed in the year 1989.Latest updated version came in 2016.The language used is Assembly C, Linux, C++ for writing it.

Works on Linux and windows operating system.

Compatible with Oracle provides efficient management of workload and allows multiple users to use the same database.

4. **SAP Sybase ASE:** ASE means adaptive server enterprise. It can perform millions of transactions in a minute, with the use of cloud and even mobile devices can be synchronized with the database.

5. **PostgreSQL:** It’s a more advanced database.Current Version is 9.6.2. Can be used across Linux and windows operating systems.

It uses object relational database.The data remains secure.Data retrieval is faster.Data sharing through dashboards is faster.

6. **ADABAS:** It means adaptable database system. Runs on Windows and Unix, Linux operating systems. Data processing speed is fast, no matter what is the load output of any transaction is reliable, it keeps pace with the changing demands the architecture is such.

7. **MySQL:** Latest version 8.Language used is C and C++. Works on Linux, Windows. High Speed of processing data, use of triggers increases productivity, with rollback and commit helps in data recovery if required.

8. **Amazon RDS:** It is also called Amazon Relational Database Service. Setting up and operating it is very easy, and the database is very secure.Backing up of the database is an inbuilt feature.Recovery of data is also inbuilt feature managed within.

9. **Microsoft Access:** Works on Microsoft Windows. It’s a file uploaded on the server created using ms access.It’s a cheap database system used by systems on the internet mostly by e-commerce sites.

10. **MongoDB:** It’s a database which can process large data simultaneously and uses internal memory so the data is easily accessible, use of very complex joins is not there, scaling is easily possible.Queries can be easily optimized for output.


## [ACID Property](https://www.geeksforgeeks.org/acid-properties-in-dbms/)
**A - Atomicity:** It mean that either the entire transaction takes place at once or doesn’t happen at all. There is no midway i.e. transactions do not occur partially. Each transaction is considered as one unit and either runs to completion or is not executed at all. It involves following two operations.

*—Abort:* If a transaction aborts, changes made to database are not visible.
*—Commit:* If a transaction commits, changes made are visible.

Atomicity is also known as the ‘All or nothing rule’. 

**C - Consistency:** This means that integrity constraints must be maintained so that the database is consistent before and after the transaction. It refers to correctness of a database. 

**I - Isolation:** This property ensures that multiple transactions can occur concurrently without leading to inconsistency of database state. Transactions occur independently without interference. Changes occurring in a particular transaction will not be visible to any other transaction until that particular change in that transaction is written to memory or has been committed. This property ensures that the execution of transactions concurrently will result in a state that is equivalent to a state achieved these were executed serially in some order.

**D - Durability:** This property ensures that once the transaction has completed execution, the updates and modifications to the database are stored in and written to disk and they persist even if system failure occurs. These updates now become permanent and are stored in a non-volatile memory. The effects of the transaction, thus, are never lost.


## [Aggregations](https://searchsqlserver.techtarget.com/definition/data-aggregation)
Data aggregation is any process in which information is gathered and expressed in a summary form, for purposes such as statistical analysis. A common aggregation purpose is to get more information about particular groups based on specific variables such as age, profession, or income.

## [Joins](http://whatisdbms.com/what-is-join-and-its-types-in-dbms/)
A [JOIN](https://www.w3schools.com/sql/sql_join.asp) clause is used to combine rows from two or more tables, based on a related column between them.

Joins in DBMS and Types (Inner, Outer, Theta, Equi, Left, Right): Joins can be simply defined as the combining or merging the related tuples from the two different relations into a single type. ... A cartesian product is followed by a selection process results in joins.


## [CAP Theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
The CAP Theorem is a fundamental theorem in distributed systems that states any distributed system can have at most two of the following three properties. Consistency. Availability. Partition tolerance.


## 7 network layers
**[Layer 7: The application layer](https://searchnetworking.techtarget.com/definition/Application-layer)**: This is the top layer of any application where the data or application is presented in a visual form the user can understand. This layer is not the application itself, it is the set of services an application should be able to make use of directly, although some applications may perform application-layer functions.

**[Layer 6: The presentation layer](https://searchnetworking.techtarget.com/definition/presentation-layer)**: This layer is usually part of an operating system (OS) and converts incoming and outgoing data from one presentation format to another -- for example, from clear text to encrypted text at one end and back to clear text at the other.

**[Layer 5: The session layer](https://searchnetworking.techtarget.com/definition/Session-layer)**: his layer sets up, coordinates and terminates conversations. Its services include authentication and reconnection after an interruption. On the internet, Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) provide these services for most applications.

**[Layer 4: The transport layer](https://searchnetworking.techtarget.com/definition/Transport-layer)**: This layer manages packetization of data, then the delivery of the packets, including checking for errors in the data once it arrives. On the internet, TCP and UDP provide these services for most applications as well.

**[Layer 3: The network layer](https://searchnetworking.techtarget.com/definition/Network-layer)**: This layer handles addressing and routing the data -- sending it in the right direction to the right destination on outgoing transmissions and receiving incoming transmissions at the packet level. IP is the network layer for the internet.

**[Layer 2: The data-link layer](https://searchnetworking.techtarget.com/definition/Data-Link-layer)**: This layer sets up links across the physical network, putting packets into network frames. This layer has two sub-layers: the logical link control layer and the media access control layer (MAC). MAC layer types include Ethernet and 802.11 wireless specifications.

**[Layer 1: The physical layer](https://searchnetworking.techtarget.com/definition/physical-layer)**: This layer conveys the bit stream across the network either electrically, mechanically or through radio waves. The physical layer covers a variety of devices and mediums, among them cabling, connectors, receivers, transceivers and repeaters.


## [Request Response Protocol](https://en.wikipedia.org/wiki/Request%E2%80%93response)
Request–response, or request–reply, is one of the basic methods computers use to communicate with each other, in which the first computer sends a request for some data and the second responds to the request. Usually, there is a series of such interchanges until the complete message is sent; browsing a web page is an example of request–response communication. Request–response can be seen as a telephone call, in which someone is called and they answer the call.

Request–response is a message exchange pattern in which a requestor sends a request message to a replier system which receives and processes the request, ultimately returning a message in response. This is a simple, but powerful messaging pattern which allows two applications to have a two-way conversation with one another over a channel. This pattern is especially common in client–server architectures.


## [HTTP](https://www.webopedia.com/TERM/H/HTTP.html)
HTTP means HyperText Transfer Protocol. HTTP is the underlying protocol used by the World Wide Web and this protocol defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands.


## [TCP](https://www.webopedia.com/TERM/T/TCP.html) 
TCP (Transmission Control Protocol) is one of the main protocols in TCP/IP networks. Whereas the IP protocol deals only with packets, TCP enables two hosts to establish a connection and exchange streams of data. TCP guarantees delivery of data and also guarantees that packets will be delivered in the same order in which they were sent.


## [UDP](https://searchnetworking.techtarget.com/definition/UDP-User-Datagram-Protocol)
UDP (User Datagram Protocol) is an alternative communications protocol to Transmission Control Protocol (TCP) used primarily for establishing low-latency and loss-tolerating connections between applications on the internet.


## [Web server](https://www.fastwebhost.in/blog/what-is-web-server-and-different-types-of-web-servers/)
Web server is a program that uses HTTP to serve files that create web pages to users in response to their requests, which is sent by their computers HTTP connection. Any server that delivers an XML document to another device can be a web server.


## [Static server](https://www.npmjs.com/package/static-server)
A simple http server to serve static resource files from a local directory.


## [Application server](https://en.wikipedia.org/wiki/Application_server)
An application server is a software framework that provides both facilities to create web applications and a server environment to run them. Application Server Frameworks contain a comprehensive service layer model.


## [DNS server](https://www.lifewire.com/what-is-a-dns-server-2625854)
A DNS server is a computer server that contains a database of public IP addresses and their associated hostnames, and in most cases serves to resolve, or translate, those names to IP addresses as requested. DNS servers run special software and communicate with each other using special protocols.


## [Database Server](https://www.webopedia.com/TERM/D/database_server.html)
Database server is the term used to refer to the back-end system of a database application using client/server architecture. The back-end, sometimes called a database server, performs tasks such as data analysis, storage, data manipulation, archiving, and other non-user specific tasks.


## [Standalone Application](https://www.quora.com/What-is-a-standalone-application)
Standalone applications are traditional software that are installed on each client system. Essence Computing only develops platform-independent applications, so that the user can use any Operating System of their choice on the system.


## [MVC](https://www.tutorialsteacher.com/mvc/mvc-architecture)
MVC stands for *Model, View and Controller.* MVC separates application into three components - Model, View and Controller. Model: Model represents shape of the data and business logic. It maintains the data of the application. Model objects retrieve and store model state in a database.


## [Operating System](https://en.wikipedia.org/wiki/Operating_system)
An operating system (OS) is system software that manages computer hardware and software resources and provides common services for computer programs.

**Types of operating systems :**
**Single- and multi-tasking**
A single-tasking system can only run one program at a time, while a multi-tasking operating system allows more than one program to be running in concurrency. This is achieved by time-sharing, where the available processor time is divided between multiple processes. These processes are each interrupted repeatedly in time slices by a task-scheduling subsystem of the operating system. Multi-tasking may be characterized in preemptive and co-operative types. In preemptive multitasking, the operating system slices the CPU time and dedicates a slot to each of the programs. Unix-like operating systems, such as Solaris and Linux—as well as non-Unix-like, such as AmigaOS—support preemptive multitasking. Cooperative multitasking is achieved by relying on each process to provide time to the other processes in a defined manner. 16-bit versions of Microsoft Windows used cooperative multi-tasking. 32-bit versions of both Windows NT and Win9x, used preemptive multi-tasking.

**Single- and multi-user**
Single-user operating systems have no facilities to distinguish users, but may allow multiple programs to run in tandem. A multi-user operating system extends the basic concept of multi-tasking with facilities that identify processes and resources, such as disk space, belonging to multiple users, and the system permits multiple users to interact with the system at the same time. Time-sharing operating systems schedule tasks for efficient use of the system and may also include accounting software for cost allocation of processor time, mass storage, printing, and other resources to multiple users.

**Distributed**
A distributed operating system manages a group of distinct computers and makes them appear to be a single computer. The development of networked computers that could be linked and communicate with each other gave rise to distributed computing. Distributed computations are carried out on more than one machine. When computers in a group work in cooperation, they form a distributed system.

**Templated**
In an OS, distributed and cloud computing context, templating refers to creating a single virtual machine image as a guest operating system, then saving it as a tool for multiple running virtual machines. The technique is used both in virtualization and cloud computing management, and is common in large server warehouses.

**Embedded**
Embedded operating systems are designed to be used in embedded computer systems. They are designed to operate on small machines like PDAs with less autonomy. They are able to operate with a limited number of resources. They are very compact and extremely efficient by design. Windows CE and Minix 3 are some examples of embedded operating systems.

**Real-time**
A real-time operating system is an operating system that guarantees to process events or data by a specific moment in time. A real-time operating system may be single- or multi-tasking, but when multitasking, it uses specialized scheduling algorithms so that a deterministic nature of behavior is achieved. An event-driven system switches between tasks based on their priorities or external events while time-sharing operating systems switch tasks based on clock interrupts.

**Library**
A library operating system is one in which the services that a typical operating system provides, such as networking, are provided in the form of libraries and composed with the application and configuration code to construct a unikernel: a specialized, single address space, machine image that can be deployed to cloud or embedded environments.


## [Kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system))
The kernel is a computer program that is the core of a computer's operating system, with complete control over everything in the system. On most systems, it is one of the first programs loaded on start-up.


## [Process](https://whatis.techtarget.com/definition/process)

_A process is an instance of a program running in a computer_. It is close in meaning to task , a term used in some operating systems. In UNIX and some other operating systems, a process is started when a program is initiated (either by a user entering a shell command or by another program).


## [Thread](https://www.geeksforgeeks.org/thread-in-operating-system/)
A thread is a path of execution within a process. A process can contain multiple threads. 


## [Apache Web Server](https://www.hostinger.in/tutorials/what-is-apache)
Apache is an open-source and free web server software that powers around 46% of websites around the world. The official name is Apache HTTP Server, and it’s maintained and developed by the Apache Software Foundation.


## [Nginx Web Server](https://www.nginx.com/resources/wiki/)
NGINX is a free, open-source, high-performance HTTP server and reverse proxy, as well as an IMAP/POP3 proxy server. NGINX is known for its high performance, stability, rich feature set, simple configuration, and low resource consumption.



## [Messaging Queue](https://www.cloudamqp.com/blog/2014-12-03-what-is-message-queuing.html)
A message queue is a queue of messages sent between applications. It includes a sequence of work objects that are waiting to be processed. A message is the data transported between the sender and the receiver application; it's essentially a byte array with some headers on top.


## [Enterprise Message Bus](https://en.wikipedia.org/wiki/Enterprise_service_bus)
An enterprise service bus (ESB) implements a communication system between mutually interacting software applications in a service-oriented architecture (SOA).


## [RabbitMQ](https://www.rabbitmq.com)
It is also a kind of Message Queue. RabbitMQ is the most widely deployed open source message broker. RabbitMQ is lightweight and easy to deploy on premises and in the cloud. It supports multiple messaging protocols. RabbitMQ can be deployed in distributed and federated configurations to meet high-scale, high-availability requirements.


## [Kafka](https://en.wikipedia.org/wiki/Apache_Kafka)
It is also known as Apache Kafka. It is an _open-source_ stream-processing software platform developed by LinkedIn and donated to the Apache Software Foundation, written in Scala and Java. The project aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds.


## [Hadoop](https://en.wikipedia.org/wiki/Apache_Hadoop)
Apache Hadoop is a collection of open-source software utilities that facilitate using a network of many computers to solve problems involving massive amounts of data and computation. It provides a software framework for distributed storage and processing of big data using the MapReduce programming model.


## [Zookeeper](https://zookeeper.apache.org)
ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services. All of these kinds of services are used in some form or another by distributed applications. Each time they are implemented there is a lot of work that goes into fixing the bugs and race conditions that are inevitable. Because of the difficulty of implementing these kinds of services, applications initially usually skimp on them, which make them brittle in the presence of change and difficult to manage. Even when done correctly, different implementations of these services lead to management complexity when the applications are deployed.


## [Service Oriented Architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)
Service-oriented architecture is a style of software design where services are provided to the other components by application components, through a communication protocol over a network. The basic principles of service-oriented architecture are independent of vendors, products and technologies.

## [Microservices Architecture](https://microservices.io)
Microservices - also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are. Highly maintainable and testable. Loosely coupled. Independently deployable. Organized around business capabilities.


## [Redis](https://redis.io)
Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache and message broker. It supports data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes with radius queries and streams. Redis has built-in replication, Lua scripting, LRU eviction, transactions and different levels of on-disk persistence, and provides high availability via Redis Sentinel and automatic partitioning with Redis Cluster.


## [Solr](https://lucene.apache.org/solr/)
Apache Solr is highly reliable, scalable and fault tolerant, providing distributed indexing, replication and load-balanced querying, automated failover and recovery, centralized configuration and more. Solr powers the search and navigation features of many of the world's largest internet sites.


## [ElasticSearch](https://en.wikipedia.org/wiki/Elasticsearch)
Elasticsearch is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java.


## [Celery](http://www.celeryproject.org/)
Celery is an asynchronous task queue/job queue based on distributed message passing.	It is focused on real-time operation, but supports scheduling as well.

The execution units, called tasks, are executed concurrently on a single or more worker servers using multiprocessing, Eventlet,	or gevent. Tasks can execute asynchronously (in the background) or synchronously (wait until ready).


## [Node JS](https://en.wikipedia.org/wiki/Node.js)
Node.js is an open-source, cross-platform, JavaScript run-time environment that executes JavaScript code outside of a browser.


## [Next JS](https://en.wikipedia.org/wiki/Draft:Next.js)
Next.js is an open source React framework for web applications built by ZEIT and the community. It is based on Node.js , Webpack and Babel and integrates with React to build single page applications, server-side rendered (SSR) and statically rendered pages.


## [MongoDB](https://www.tutorialspoint.com/mongodb/index.htm)
MongoDB is an open-source document database and leading NoSQL database. MongoDB is written in C++. This tutorial will give you great understanding on MongoDB concepts needed to create and deploy a highly scalable and performance-oriented database.


## [Django](https://www.djangoproject.com/)
Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It's free and open source. Ridiculously fast.


## [Django REST Framework](https://www.django-rest-framework.org/)
Django REST framework is a powerful and flexible toolkit for building Web APIs. The Web browsable API is a huge usability win for your developers.

Some reasons you might want to use REST framework:

* The Web browsable API is a huge usability win for your developers.
* Authentication policies including packages for OAuth1a and OAuth2.
* Serialization that supports both ORM and non-ORM data sources.
* Customizable all the way down - just use regular function-based views if you don't need the more powerful features.
* Extensive documentation, and great community support.
* Used and trusted by internationally recognised companies including Mozilla, Red Hat, Heroku, and Eventbrite.


## [Progressive Web Apps (PWA)](https://ionicframework.com/docs/v3/developer-resources/progressive-web-apps/)
A Progressive Web App (PWA) is a web app that uses modern web capabilities to deliver an app-like experience to users. These apps meet certain requirements (see below), are deployed to servers, accessible through URLs, and indexed by search engines.


## [Session Based Authentication](https://medium.com/@sherryhsu/session-vs-token-based-authentication-11a6c5ac45e4)
In the session based authentication, the server will create a session for the user after the user logs in. The session id is then stored on a cookie on the user’s browser. While the user stays logged in, the cookie would be sent along with every subsequent request. The server can then compare the session id stored on the cookie against the session information stored in the memory to verify user’s identity and sends response with the corresponding state!


## [Token Based Authentication](https://medium.com/@sherryhsu/session-vs-token-based-authentication-11a6c5ac45e4)
Many web applications use JSON Web Token (JWT) instead of sessions for authentication. In the token based application, the server creates JWT with a secret and sends the JWT to the client. The client stores the JWT (usually in local storage) and includes JWT in the header with every request. The server would then validate the JWT with every request from the client and sends response.


## [Authorization](https://en.wikipedia.org/wiki/Authorization)
Authorization is the function of specifying access rights/privileges to resources, which is related to information security and computer security in general and to access control in particular. More formally, "to authorize" is to define an access policy.


## [Docker](https://en.wikipedia.org/wiki/Docker_(software))
Docker is a set of platform-as-a-service products that use operating-system-level virtualization to deliver software in packages called containers.


## [IaaS](https://searchcloudcomputing.techtarget.com/definition/Infrastructure-as-a-Service-IaaS)
Infrastructure as a service (IaaS) is a form of cloud computing that provides virtualized computing resources over the internet. IaaS is one of the three main categories of cloud computing services, alongside software as a service (SaaS) and platform as a service (PaaS).


## [AWS](https://en.wikipedia.org/wiki/Amazon_Web_Services)
AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage and content delivery services.

AWS launched in 2006 from the internal infrastructure that Amazon.com built to handle its online retail operations. AWS was one of the first companies to introduce a pay-as-you-go cloud computing model that scales to provide users with compute, storage or throughput as needed.

AWS offers many different tools and solutions for enterprises and software developers that can be used in data centers in up to 190 countries. Groups such as government agencies, education institutions, nonprofits and private organizations can use AWS services.

## How AWS works:
AWS is separated into different services; each can be configured in different ways based on the user's needs. Users should be able to see configuration options and individual server maps for an AWS service.


## [PaaS](https://searchcloudcomputing.techtarget.com/definition/Platform-as-a-Service-PaaS)
Platform as a service (PaaS) is a cloud computing model in which a third-party provider delivers hardware and software tools -- usually those needed for application development -- to users over the internet. A PaaS provider hosts the hardware and software on its own infrastructure.


## [Heroku](https://en.wikipedia.org/wiki/Heroku)
Heroku is a cloud platform as a service supporting several programming languages. One of the first cloud platforms, Heroku has been in development since June 2007, when it supported only the Ruby programming language, but now supports Java, Node.js, Scala, Clojure, Python, PHP, and Go.
