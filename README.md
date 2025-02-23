# Unhandled Exception Error in Node.js

This repository demonstrates an example of an unhandled exception error in a Node.js application and how to handle it using try...catch blocks.

## Bug

The `bug.js` file contains a simple HTTP server. However, it lacks proper error handling, leading to an unhandled exception if an error occurs during the server's operation.

## Solution

The `bugSolution.js` file demonstrates how to implement a try...catch block to handle potential exceptions and prevent the application from crashing.

## How to reproduce

1. Clone this repository
2. Navigate to the repository directory
3. Run `node bug.js`
4. Observe the unhandled exception error
5. Run `node bugSolution.js` to see how to handle the exception