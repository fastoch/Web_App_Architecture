# Definitions

REST (**Representational State Transfer**) is an **architectural style** for designing **networked applications**.

It's important to understand that **HTTP traffic** is not just made of **web pages**, there's also **REST calls**.  
And REST calls power just about every Web and Mobile App there is.  

REST calls, also known as **RESTful API requests**, are a way for client applications to communicate with servers  
and interact with resources over the Internet.

---

# Key concepts 

REST calls adhere to the following principles:
- **Client-Server Separation**: The client and server are independent, allowing them to evolve separately
- **Statelessness**: each request from the client contains all necessary information, the server doesn't store client context between requests
- **Resource-Based**: REST APIs are centered around resources, which are any data or services that can be accessed by the client

---

# HTTP Methods

REST calls use standard HTTP methods to perform operations on resources:
- **GET**: Retrieve a resource
- **POST**: Create a new resource
- **PUT**: Update an existing resource
- **DELETE**: Remove a resource

---

# Components of a REST call

A typical REST call consists of:
- **HTTP Method**: Specifies the action to be performed (GET, POST, etc.)
- **Endpoint**: The URL that identifies the requested resource
- **Headers**: Additional information about the request or response
- **Body**: Optional data sent with the request (for POST or PUT methods)

---

# Benefits of REST calls

- **Simplicity**: REST uses standard HTTP methods, making it easy to understand and implement
- **Scalability**: the stateless nature of REST calls allows for better scalability
- **Flexibility**: REST supports multiple data formats, including JSON and XML

---
EOF
