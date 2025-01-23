# Node.js Unhandled Exception Bug

This repository demonstrates a common error in Node.js: unhandled exceptions in HTTP servers.  The `bug.js` file shows an example of an HTTP server that crashes upon encountering an error, and `bugSolution.js` shows how to handle this error gracefully.

## Bug
The `bug.js` file contains an HTTP server. When you navigate to `/error`, an exception is thrown, causing the server to crash and exit.

## Solution
The `bugSolution.js` file demonstrates how to add error handling using a `try...catch` block within the HTTP server's request listener.  This prevents the server from crashing, allowing for better error handling and logging.