# Node.js Basic

This repository contains solutions to a series of tasks focused on basic Node.js concepts and web server development using modules like `http` and `express`.

## Table of Contents

1. [Task 0: Executing basic JavaScript with Node.js](#task-0-executing-basic-javascript-with-nodejs)
2. [Task 1: Using Process stdin](#task-1-using-process-stdin)
3. [Task 2: Reading a file synchronously with Node.js](#task-2-reading-a-file-synchronously-with-nodejs)
4. [Task 3: Reading a file asynchronously with Node.js](#task-3-reading-a-file-asynchronously-with-nodejs)
5. [Task 4: Creating a small HTTP server using Node.js's HTTP module](#task-4-creating-a-small-http-server-using-nodejss-http-module)
6. [Task 5: Creating a more complex HTTP server using Node.js's HTTP module](#task-5-creating-a-more-complex-http-server-using-nodejss-http-module)
7. [Task 6: Creating a small HTTP server using Express](#task-6-creating-a-small-http-server-using-express)
8. [Task 7: Creating a more complex HTTP server using Express](#task-7-creating-a-more-complex-http-server-using-express)
9. [Task 8: Organizing a complex HTTP server using Express](#task-8-organizing-a-complex-http-server-using-express)

## Task 0: Executing basic JavaScript with Node.js

In this task, we created a function `displayMessage` in the file `0-console.js` that prints a string to the console.

## Task 1: Using Process stdin

The program `1-stdin.js` interacts with the user, asking for their name and displaying it back.

## Task 2: Reading a file synchronously with Node.js

The function `countStudents` in `2-read_file.js` reads a CSV file synchronously and logs the number of students in each field.

## Task 3: Reading a file asynchronously with Node.js

Similar to Task 2, but the function `countStudents` in `3-read_file_async.js` reads the file asynchronously.

## Task 4: Creating a small HTTP server using Node.js's HTTP module

In `4-http.js`, a small HTTP server is created using the `http` module. It listens on port 1245 and responds with "Hello Holberton School!" for any endpoint.

## Task 5: Creating a more complex HTTP server using Node.js's HTTP module

`5-http.js` extends the functionality of Task 4 by providing different responses based on the URL path.

## Task 6: Creating a small HTTP server using Express

In `6-http_express.js`, a small HTTP server is created using the Express framework. It listens on port 1245 and responds with "Hello Holberton School!".

## Task 7: Creating a more complex HTTP server using Express

`7-http_express.js` extends the functionality of Task 6 by providing different responses based on the URL path using Express.

## Task 8: Organizing a complex HTTP server using Express

A more structured approach is taken in `full_server` directory. The server's components are organized into controllers, routes, and utilities, utilizing Express.

Each task has its own README file with detailed instructions and examples.

## Repository Structure

- `0x05-Node_JS_basic/`: Main directory containing all the tasks.
- `0-console.js` to `7-http_express.js`: Files containing the solutions for each task.
- `full_server/`: Directory containing the files for Task 8.

For detailed instructions on each task, please refer to the individual README files within each task's directory.

## How to Run

1. Clone this repository.
2. Navigate to the desired task directory.
3. Run the JavaScript file using Node.js. For example: `node 1-stdin.js`

Feel free to explore the repository for more information on each task.

## Author

This repository is maintained by [Yabs Mullo].
