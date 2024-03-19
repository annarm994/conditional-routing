Assignment 7

# Conditional Routing Express Server

This is a Node.js Express server that demonstrates conditional routing based on certain conditions.

## Instructions

To run the server, follow these steps:

1. Clone the repository
2. npm install
3. node app.js

# Conditional Routing Implementation
In this server, conditional routing is implemented using Express.js. There are two route handlers for the path '/foo':

The first route handler randomly chooses between two responses: "sometimes this" and passing control to the next applicable route using the next() method.
The second route handler for the same path always returns the response "and sometimes that".

# Evaluation Criteria
Proper implementation of conditional routing in Express.
Correct setup and configuration of the Express server.
