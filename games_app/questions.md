Questions:

What is responsible for defining the routes of the games resource?
A = The Server is responsible because is receiving the data.

What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
A= I noticed that Games_app is divided in two main folders: Client/Server.
Client is responsible of rendering the pages, making requests and using the server data response.
Server is responsible of receiving clients requests and send the data to the database.  

What are the the responsibilities of server.js?
A: Initiate the database connection, select database and Initiate the web server.

What are the responsibilities of the gamesRouter?
A: gameRouter is responsible of defining the routes that will be available in the web server.

What process does the the client (front-end) use to communicate with the server?
A: The client communicates with the server through request which are made by fetch.

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
A: The second argument allows us to define the options, body and headers of the request.

Which of the games API routes does the front-end application consume (i.e. make requests to)?
A: When the app is mounted this will be made a request to the endpoint: router.get('/', (req, res)

What are we using the MongoDB Driver for?
A: We are using MongoDB to store data(JSON).
