# Questions

## What is responsible for defining the routes of the games resource?

Express

## What do you notice about the folder structure? Whats the client responsible for? 

It is split into the front-end(client) and back-end(server) folders. The client side is responsible for containing the front-end code such as the React app files / html and css.

## Whats the ## server responsible for?

The server side is responsible for the back-end code such as the Express routes and database files.

## What are the the responsibilities of server.js?

It initializes an express app and holds the routes.

## What are the responsibilities of the gamesRouter?

The gamesRouter creates the CRUD routes for the users inputs.

## What process does the the client (front-end) use to communicate with the server?

Fetch requests to the user made api

## What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

Options, which are custom setting the user wants to apply to the request.

## Which of the games API routes does the front-end application consume (i.e. make requests to)?

http://localhost:9000/api/games/

## What are we using the MongoDB Driver for?

The store the user inputs in a DB.