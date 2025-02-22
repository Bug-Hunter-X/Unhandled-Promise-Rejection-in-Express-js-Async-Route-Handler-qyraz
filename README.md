# Unhandled Promise Rejection in Express.js Async Route Handler

This repository demonstrates a common error in Express.js applications: unhandled promise rejections in asynchronous route handlers.  The `bug.js` file showcases the issue, where an asynchronous operation (`someAsyncOperation`) can throw an error, but lacks proper error handling. This leads to the server crashing without a clear indication of the problem.

The solution, provided in `bugSolution.js`, demonstrates how to properly handle these rejections using `.catch()` to gracefully manage errors and prevent server crashes.  Always ensure comprehensive error handling in your asynchronous Express.js routes to create robust and reliable applications.
