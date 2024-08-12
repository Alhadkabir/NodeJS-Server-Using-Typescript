# NodeJS-Server-Using-Typescript

Here’s an example of how to create a simple HTTP server in Node.js using TypeScript:
**
   1. First, you need to create a new directory for your project and navigate to it in the terminal.
   2. Initialize a new TypeScript project with the following command:**

  > npm init -y

   **3. Install the necessary dependencies:**

  > npm install --save-dev typescript ts-node nodemon @types/node
 
  `typescript` and `ts-node` are required for compiling and running TypeScript code. `nodemon` is a utility that monitors changes in your code and automatically restarts the server when necessary.   `@types/node` provides TypeScript definitions for Node.js.

 1. Start the server by running the following command in the terminal:

    > npm run start

 2. This should start the server and output the following message in the terminal:
    
    > Server running at http://127.0.0.1:3000/
