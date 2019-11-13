# Project NODE EXPRESS C1 Routers and Middleware

Topics: This File Is Too Big!
, Express.Router
, Using Multiple Router Files
, Matching In Nested Routers
, Middleware
, DRYing Code With Functions
, DRYing Routes With app.use()
, next()
, Request And Response Parameters
, Route-Level app.use() - Single Path
, Control Flow With next()
, Route-Level app.use() - Multiple Paths
, Middleware Stacks
, Open-Source Middleware: Logging
, Documentation
, Open-Source Middleware: Body Parsing
, Error-Handling Middleware
, Discovering Open-Source Middleware
, Router Parameters
, router.param()
, Merge Parameters

## Project Title: Email

1. Create a folder with your name like `yourname` in this folder.

2. Inside `yourname` folder create a javascript file named `index.js`.

3. Open VS Code and edit `index.js` to Log "Your Name" into console.

4. Install nodemon by running `npm install -g nodemon`

5. Run `nodemon index.js` to see your change into terminal as you up update the code.
   Note: For next steps, edit `index.js`and save it to see the result.

7. Create file `emailRouter.js` and export `emailRouter`

8. Use `emailRouter` in `index.js` to route address prepended with `emails`

9. Create array `emails` with 5 sample emails and each email object has following data: `id`, `sender`, `receiver`, `title` and `isOpened`

10. `emailRouter` should have 2 route: First is `/` for listing all emails and second is `/:id` to show an specific email.

11. Define a middleware to log any request has been sent to `emailRouter`. It should log the `Request sent at date/time`.

12. Define a middleware for `/emails/:id`. If `id` is `0` send `404` error and do not pass the request to next step. If it is not then set the id as `req.emailId`

13. Use `req.emailId` at the handler of `/emails/:id` in  `emailRouter.js` to log into console.



## Want to get reviewed?

Send Pull Request. Check how to deliver your code: https://codingwithbasir.com/how-to-deliver-projects/

## Need help?

Download Free eBook https://codingwithbasir.com/download
