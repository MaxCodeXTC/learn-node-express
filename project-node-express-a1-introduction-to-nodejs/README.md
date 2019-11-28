# Project NODE EXPRESS A1 Introduction to Nodejs

Topics: What is BACK-END
, What is Node.JS
, The Node REPL
, Running a Program with Node
, Accessing the Process Object
, Core Modules and Local Modules
, Node Package Manager
, Event-Driven Architecture
, Asynchronous JavaScript with Node.js
, User Input/Output
, Errors
, Filesystem
, Readable Streams
, Writable Streams
, Create an HTTP Server

## Project Title: Show Info

1. Create a folder with your name like `yourname` in this folder.

2. Inside `yourname` folder create a javascript file named `index.js`.

3. Open VS Code and edit `index.js` to Log `Hello World` into console.

4. Open terminal and go to `yourname` folder and run `node index.js`.
   Note: Check `Hello World` into console and exit by pressing Ctrl+C.

5. Install nodemon by running `npm install -g nodemon`

6. Run `nodemon index.js` to see your change into terminal as you up update the code.
   Note: For next steps, edit `index.js`and save it to see the result.

7. Log environment variables. If `NODE_ENV` is `development` log `This app is under test.`.

8. Log how many bytes of memory the current process is using.

9. Import `os` module and log `Platform` and `Architecture` of your computer.

10. Create file name `info.js` and create class `info` there.

11. Add `title`, `owner` and `createTime` to this class and change constructor to accept values for these fields.

12. Add `getInfo` method that return an object like `Note {title} is created by {title} at {createTime}`.

13. Import newly created file `info.js` into `index.js` and create instance from `info` class with sample values.

14. Class getInfo and log it into console.

15. Define variable named `canExit` and set to `false`. Define a function named `readyToExit` that set `canExit` to `true` and log `I'm out.`

16. Run `readyToExit` after 3 seconds. Note: Use `setTimeout`.

17. Create a while loop that run as long as `canExit` is `false`. Inside this loop, log `I'm in`.

18. Run `readyToExit` every 2 seconds. Use `setInterval`

## Want to get reviewed?

Send Pull Request. Check how to deliver your code: https://codingwithbasir.com/how-to-deliver-projects/

## Need help?

Download Free eBook https://codingwithbasir.com/download
