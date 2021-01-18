# HMW-full-stack-app-prep
What is responsible for defining the routes of the games resource?
  - The express is responsible for the routes of the games resource.

What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
 - The folder structure holds our front and back sides, Including databases events , routes and components
 - Client is responsible for front end work such as events and components.
 - Server is responsible for the backend such as our databases and routes.

What are the the responsibilities of server.js?
 - The theIt holds the cors which holds security functionality letting the hosts talk to each other.
 - It holds our parser.json which allows to access the body.
 - It holds our database.
 - It holds listen which listens out for our route calls 


What are the responsibilities of the gamesRouter?
 - Games router is a variable which is equal to create router which links us to the create router file which holds all of our routes in. 


What process does the the client (front-end) use to communicate with the server?
	- The client communicates with the server through the api.

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using  Fetch on the MDN docs?

 - The optional second argument that the fetch method can take is an init object and it is used to control a number of    different settings such as a post method.

Which of the games API routes does the front-end application consume (i.e. make requests to)?
What are we using the MongoDB Driver for?
 - POST, DELETE and GET
 - MongoDB Node.js driver allows Node.js applications to connect to MongoDB and work with data

