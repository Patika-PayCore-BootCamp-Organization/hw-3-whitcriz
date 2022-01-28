## PATIKA & PAYCORE JAVA SPRING BOOTCAMP

### ANSWERS TO WEEK-3 HOMEWORK QUESTIONS

---

#### Q1 - SOAP vs Restful ?

---

Application Programming Interfaces (APIs) provide a secure and standardized way for different software to communicate to each other. In other words, an application can extract functionality or data from another piece of software and use it to enhance its own functionality or UX.  The communication method, how we make this communication, depends on how the API was built. The two most common methods are RESTful and SOAP methods.

Simple Object Access Protocol (SOAP) is a standard communication protocol system that uses XML technologies to build APIs and maintained by the World Wide Web Consortium (W3C). SOAP was first designed in order to allow applications running on different operating systems to communicate using different languages and technologies. So, it imposes built-in rules that increase its complexity and overhead, which can lead to longer page load times. However, these standards also offer built-in compliances that can make it preferable for enterprise scenarios. The built-in compliance standards include security, Atomicity, Consistency, Isolation, and Durability (ACID), which is a set of properties for ensuring reliable database transactions. A client can use SOAP APIs to create, retrieve, update or delete records, such as passwords, accounts, leads, and custom objects, from a server.

RESTful APIs follows REST (REpresentational State Transfer) architectural principles that uses a simpler, solitary, consistent and more flexible method for building APIs. In order to understand a RESTful approach, we need to understand REST principles first. REST  is a set of architectural principles attuned to the needs of lightweight web services and mobile applications by defining how to build APIs, which allow data to be communicated between web applications.   Because it's a set of guidelines, it leaves the implementation of these recommendations to developers.

A RESTful application must have these guidelines:
- A client-server architecture composed of clients, servers, and resources.
- Stateless client-server communication, meaning no client content is stored on the server between requests. Information about the session’s state is instead held with the client.
- Cacheable data to eliminate the need for some client-server interactions.
- The central feature that distinguishes the REST architectural style from other network-based styles is a uniform interface between components so that information is transferred in a standardized form instead of specific to an application’s needs.
- A layered system constraint, where client-server interactions can be mediated by hierarchical layers.
- Code on demand, allowing servers to extend the functionality of a client by transferring executable code (though also reducing visibility, making this an optional guideline).


Differences between SOAP and RESTful:

| SOAP | RESTful |
|---------|-----------|
| A type of protocol and consists of an official standard, so very strict. | An architectural style, so more flexible |
| Developing private APIs, especially for large enterprises, since SOAP allows data to be transferred in a decentralized, distributed environment and has lots of web security mechanisms  | Developing public APIs to access data |
| Using an underlying transport protocol other than HTTP: SMTP (Simple Mail Transfer Protocol) or JMS (Java Messaging Service) or TCP or another transport protocol, depending on your application.  | Access web services by using HTTP. |
| Return SOAP messages must be returned as XML documents—a markup language that is both human- and machine-readable.  | Return data in a variety of formats, including XML as well as plain text, HTML, and JSON. |
| Not cacheable by a browser, so it cannot be accessed later without resending to the API. | Cacheable for information that’s not altered and not dynamic because of working with staless operations, thanks to JSON |
| Ideal for internal data transfers and other sensitive tasks, because defines its own security. | Offers better support for browser clients, because inherits security measures from the underlying transport. |
| SOAP web services offer built-in security and transaction compliance that align with many enterprise needs, but that also makes them heavier.  | Lightweight, making them ideal for newer contexts like the Internet of Things (IoT), mobile application development, and serverless computing. |
| Working with stateful operations, so requires more server resources and bandwidth, it’s important if performing repetitive or chained tasks, like bank transfers. | Working with stateless operations, so uses limited server resources and less bandwidth. |
| Offers built-in retry logic to compensate for failed communications.  | Doesn’t have a built-in messaging system. If a communication fails, the client has to deal with it by retrying. There’s also no standard set of rules for REST. This means that both parties (the service and the consumer) need to understand both content and context. |
| Highly extensible through other protocols and technologies. In addition to WS-Security, supports WS-Addressing, WS-Coordination, WS-ReliableMessaging, and others on W3C. | Only support traditional web security mechanisms, such as HTTPS, Secure Socket Layer (SSL). |
| Uses services interfaces to expose the business logic. | Uses URI to expose business logic. |



---

#### Q2 - Difference between acceptance test and functional test ?

---

