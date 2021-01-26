# Web Development

## Socket
- A __*socket*__ is an endpoint in a two way network communication. 
- It is bound to a port number so that the TCP layer could identify the corresponding app.
- An endpoint is a combination of an IP adress and a port number.

## API
- Application Programming Interface represents the contract/specification that a software program will grant to another software program that needs to perform some operations.
- Expose interfaces/entry-points so that the client won't need to know about the implementation.
- API Specification:
  - Business operation;
  - URL or interface;
  - Protocol and method;
  - Request structure;
  - Response structure;
  - Authentication/Authorization information;
  - Status codes;

## REST 
- REpresentational State Transfer is an architectural style for distributed hypermedia systems.
- A truly RESTful API looks like hypertext.
- Presented in 2000 by Roy Fielding.

### REST Principles
1. Client-Server: Separation of concerns between client and server.
2. Stateless: The requests should be self-contained and independent of previous or future ones.
3. Cacheable: The data within a response needs to be labeled as cacheable or non-cacheable.
4. Uniform interface: 
   1. Identification of resources;
   2. Manipulation of resources through representations;
   3. Self-descriptive messages;
   4. Hypermedia as the engine of the app;
5. Layered system: Architecture composed by multiple layers.
6. Code on demand: Extend the system by adding new modules.

### Resource
- The key abstraction for information.
- The resource has an identifier.
- The state of the resource is called resource representation.
- The data format of a representation is called media type.
- Any information that can be named: document, image, temporal service, collection of other resources, etc.

### Hypertext (Hypermedia)
- Simultaneous presentation of information and controls to other resources.
- Different media types.
- Every media type defines a processing model.

### Resource Methods
- A set of predefined uniform interfaces that used to perform the desired actions.
- Query based API results should be represented by a list of links withsummary information, not by arrays of original resource representations.
-  Data and functionality are considered resources and are accessed using Uniform Resource Identifiers (URIs). 