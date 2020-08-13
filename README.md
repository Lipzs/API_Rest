# API_Rest
 A simple API with rest, just for learning

 ## what is API?

 - API (Application Programming Interface) 
is basically a group of routines and patterns established by an application, for other applications can use the functionality of this application.

## what is REST?

- REST (REpresentational State Transfer) REST defines some obligations in data transfer, usually with HTTP protocol.

## what is RESTful?

### Your REST API must have 6 constraints to be RESTful. Are they:

  - _Client-server_: Separation of client and data storage (server).

  - _Stateless_: Each requisition from the client to the server, must have all the necessary information for the server understand and response the requisition. The server cannot store information from the previous requisition (state).

  - _Cacheable_: The responses to one requisition must be explicit to say if that requisition can or not be cacheable for the client. 

  - _Layered System_: The client don't need to knows the layers which the server is accessing to response the requisition. 

  - _Uniform Interface_: The uniform interface simplifies and decouples the architecture, which enables each part to evolve independently.

  - _Code On Demand(optional)_: Make it possible for the application to take codes, such as JavaScript, for example, and execute them on the client. 

---

## Status of the Responses.

- 1xx: information
- 2xx: sucess
  - 200: Ok
  - 201: Created
  - 204: Don't have content PUT POST DELETE
- 3xx: Redirection
- 4xx: Client Error
  - 400: Bad Request
  - 404: Not Found
- 5xx: Server Error
  - 500: Internal Server Error
---

### I used the software [_Insomnia_](https://insomnia.rest/) to test the routes.

- Disclaimer: the information was obtained by a video from [RocketSeat](https://rocketseat.com.br/) on YouTube and at the following link: https://stackoverflow.com/questions/25172600/rest-what-exactly-is-meant-by-uniform-interface
