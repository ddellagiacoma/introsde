IntroSDE@UniTN
============

Lab resources, code samples and other materials used in the course about [Introduction to Service Design and Engineering][1], developed at the [Department of Information Engineering and Computer Science][2] of the [University of Trento, Italy][3]. 

## Lab Modules Index

Each module is prepared to match one hands-on session. However, depending on how fast we move forward in reality, it might be that some modules take less than one session, while other take more. 

* **[LAB01: Introduction to the Lab and Brief Java Review][4]**: Introduction to the course by taking a brief look to the architecture of the web and looking at where our work will concentrate within that architecture. Review of the tools and technologies we will use, with emphasis on the programming language: Java. For those without experience in Java, there will be a brief hands on tutorial. 

* **[LAB02: Java Exercises. Ant. First service example with Axis2][5]**: Some more of Java with Eclipse as IDE. Learn about some build automation through Apache Ant. Exposed Java methods as services with Axis2 as our first glimpse to the implementation of the SOA world.

* **[LAB03: A first view to XML, XPATH & XML Schemas][6]**: How do services communicate? What's the language in which messages traverse the realms of SOAs?. In this module, we will give a look to the cornerstone language of service-oriented architectures: XML. We will do so by exploring a framework for navigating the content of an xml programmatically.  We will also explore very briefly how to define and validate XML Schemas. 

* **[LAB04: Mapping XML (and JSON) to (and from) Objects][7]**: To facilitate the lives of programmers around the world (at least for some), a long time ago we humans created object-oriented programming. But how do we go from objects to serialized representations of them in XML or JSON? And viceversa?. In this module, we will be mapping XML/JSON from and to Objects. What we covered up to here is also the base-ground we need before we start implementing actual services.

* **[LAB05: The REST architectural style & RESTful web services (1)][8]**: Whenever we talk about the World Wide Web, and its underlying architectural principles, what we are really talking about is of REST. What is to say, the Representational state transfer is an abstraction of the architecture of the WWW. In this module, we will explore the basis for designing and implementing services following this architectural style.   

* **[LAB06: CRUD RESTful Services (2)][9]**: In its first installment, we have explored the principles behind the REST architectural style and how to create a simple read-only RESTful web service. In this module, we will deepen our understanding by implement a set of CRUD RESTful services for our Health Profile example.

* **[LAB07: Reading and writing from Databases & JPA (Java Persistence API)][10]**: To close the loop of our service design, we will need to store (i.e., persist) our data in real databases. Nowadays, there are two major flavours of databases: relational and non-relational (also NoSQL). In this module, we will add database access to our RESTful services using the Java Persistence API (JPA). We will do so using SQLite as the exemplary relational database. If we have some time, we might also explore a non-relational database example. 

* **[LAB08: SOAP Web Services (1)][11]**: Last, but not least, your knowledge of service design and engineering would not be complete if you do not know how to implement services following the SOAP protocol. In this module, we will get acquainted with JAX-WX as the framework for implementing SOAP services. 

* **[LAB09: SOAP Web Services (2)][12]**: A second look to implementing SOAP web services using JAX-WS, adding JPA to access databases. 


The code in this repository is an update of the original trunk of source code of the 2013 session, available at [introsde2013][13]. In each session, a README.md file contains all the instructions and related concepts.  



[1]: https://sites.google.com/site/introsdeunitn/
[2]: http://www.disi.unitn.it/
[3]: http://www.unitn.it/
[4]: https://github.com/ddellagiacoma/introsde/tree/master/lab01
[5]: https://github.com/ddellagiacoma/introsde/tree/master/lab02
[6]: https://github.com/ddellagiacoma/introsde/tree/master/lab03
[7]: https://github.com/ddellagiacoma/introsde/tree/master/lab04
[8]: https://github.com/ddellagiacoma/introsde/tree/master/lab05
[9]: https://github.com/ddellagiacoma/introsde/tree/master/lab06
[10]: https://github.com/ddellagiacoma/introsde/tree/master/lab07
[11]: https://github.com/ddellagiacoma/introsde/tree/master/lab08
[12]: https://github.com/ddellagiacoma/introsde/tree/master/lab09
[13]: https://github.com/IntroSDE/introsde2013
