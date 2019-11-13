# Project NODE EXPRESS B1 Introduction to Express

Topics: What is Express?
, Starting A Server
, Writing Your First Route
, Sending A Response
, Matching Route Paths
, Getting A Single Resource
, Setting Status Codes
, Matching Longer Paths
, Other HTTP Methods
, Using Queries
, Matching By HTTP Verb
, Creating A Resource
, Deleting A Resource

## Project Title: Product Items

1. Create a folder with your name like `yourname` in this folder.

2. Inside `yourname` folder create a javascript file named `index.js`.

3. Open VS Code and edit `index.js` to Log "Your Name" into console.

4. Install nodemon by running `npm install -g nodemon`

5. Run `nodemon index.js` to see your change into terminal as you up update the code.
   Note: For next steps, edit `index.js`and save it to see the result.

6. Create array `items` that show list of 5 item. Each item has `id`, `name`, `price` , `sellerId` and `inStock` property. 

7. Create a route for list of products at `/prodcuts`.

8. Create a route for a specific product at `/prodcuts/:id`. If a product with requsted `id` does not found return `404` code and say `Product Not Found`.

9. Create a route for adding a product in `items` arrays at `/products` as POST request. If the id is duplicate it should send `400` error and say `Product is duplicate. Use another id`

10. Create a route for updating a product in `items` arrays at `/products` as PUT request. It should prevent updating `sellerId` and set `400` error and say `Seller can not be changed`.

11.   Create a route for deleting a product in `items` arrays at `/products` as PUT request. It inStock is true it should not delete the item and return `You can not an item in stock`.

12. Use PostMan to test all above apis.
 

## Want to get reviewed?

Send Pull Request. Check how to deliver your code: https://codingwithbasir.com/how-to-deliver-projects/

## Need help?

Download Free eBook https://codingwithbasir.com/download
