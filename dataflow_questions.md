---What is responsible for defining the routes of the games resource?
The create_router.js file in the server/helpers directory. 


---What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

The server (backend) seeds the database and defines the routes used to access and modify the 'games' database. The client (frontend) presents the full list of games as html templates, as well as details about a game when it is clicked on.


---What are the the responsibilities of server.js?

Server.js is used to include dependencies and Mongo.


---What are the responsibilities of the gamesRouter?

The games Router is used in the createRouter function in order to automatically create routes to access the games database. 


---What process does the the client (front-end) use to communicate with the server?

The GamesService.js contains fetch methods to get (all), post a new game and delete an existing one. 


---What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

A second argument for the fetch method can be used to post JSON data, in this case to the games database.


---Which of the games API routes does the front-end application consume (i.e. make requests to)?

'/' and '/:id'


---What are we using the MongoDB Driver for?


For (asynchronous) promises from the server to the client.
