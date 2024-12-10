# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js servers: unresponsiveness caused by long-running operations that block the event loop.  The `server.js` file contains code that simulates a 5-second delay within the request handler.  This prevents the server from responding to other requests during that time.

The solution, `serverSolution.js`, demonstrates how to use asynchronous techniques (e.g., `setTimeout`) to prevent blocking. 