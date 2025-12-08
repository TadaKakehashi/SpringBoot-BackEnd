# SpringBoot-BackEnd


## Client:
A device or application that requests services or resources from a server.

-> Clien will have user interface

-> Clients main concern is requesting services

-> Client Receives Data

## Server:
A device or application that provides resources to clients, Servers are designed to handle requests from multiple clients.

-> Servers are always on, operational and connected to internet

-> Can handle multiple requests

-> They are designed to send Data

## APIs (Application Programming Interface):
Sets of rules or application that helps two software application to communicate with each other.

Types of APIs:
1) Private (Internal APIs not available to Public)
2) Partner (APIs that are shared to a partner for operation purposes only and is not available to Public)
3) Public APIs

Types of API Requests:
1) GET Request: Retrieve or Get Resources from server (Used only to read data)
2) Post Request: Create Resources from server
3) Put Request: Update existing resources on Server (update only)
4) Delete Request: Used to delete resources from the server

## REST API (Representational State Transfer) 
-> Rest is Stateless (Server wont save client data or client interactions with server, as it only checks the request)

*Web services that are built following the REST architectural style are known as RESTful web services*

## http & https
Both are protocols designed for transferring hypertext across the World Wide Web
-> They both operate based on a client-server model, where a client sends a request to the server hosting a website.

-> HTTP and HTTPS are both stateless protocols, meaning they do not inherently remember anything about the previous web session.

## Status Codes in API:-
When APIs communinate to they use Status Code to indicate the result of the request.

Classification of Status Code:-

-> 1xx (Information) 

-> 2xx (Successful)  { __200__ OK Standard response for a succedul response ; __201__ Create(user creation or product); __204__ No Content } 

-> 3xx (Redirection)  { __301__ Moved Permanently }

-> 4xx (Client Error)  { __400__ Bad Request (Syntax or parameters are not right); __401__ Unauthorized; __403__ Forbidden; __404__ Not Found }

-> 5xx (Server Error)  { __500__ Internal Server Error }

## Resource: 
Any piece of information that can be named or identified on the web.

-> Can represent any type of object, data or service that can be accessed by clients.

-> In a social media application, resouces could include a user profile, a photo, a list of friends, or even a specific post or comment.

## URI (Uniform Resource Identifier):
A URI is a string of characters used to identify a resource on the internet either by location, name or both.
URIs are a broad category that includes both URLs (Uniform Resource Locators) and URNs (Uniform Resource Names).

## Sub-Resource:
-> It is a resource that is hiearchically under another resouce.

-> It's a part of a larger resouce and can be accedded by extending the URI of the parent resouce.

-> They are often used in RESTful APIs

----

## Coupling
Coupling refers to how closely connected different components or systems are.
1) *Tight Coupling*: Describes a scenario where software componets are __highly dependent__ on each other
3) *Loose Coupling*: Describes a scenario where software components are __less dependent__ on each other

*Loosely Coupled Systems are Flexible and Maintain, as well as are Scalable* 

#### *How to Achieve Loose Coupling:*
-> Interfaces and Abstraction

-> Dependency Injection

-> Event Driven Architecture
