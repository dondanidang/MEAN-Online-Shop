This application was built during the EDX's MOOC course called Introduction to mongoDB
using MEAN stack. It is an online book shop where users can:
  - Search for a product
  - Add/update a product to their cart
  - Authenticate with facebook before to checkout your cart

=========================== What I learnt=======================================
  1. Schema design for MongoDB
  2. API with expressJS  
  3. AngularJS for webApp
  4. Ionic framework for hybrid App
  5. OAuth with passportJS
  6. Online payment with StripeJs
  7. Task runner and TDD with gulp, mocha

=================================IMPORTANT======================================
The tests have been done in chrome, so use it if possible.
================================================================================

========================= Running the server ===================================
  1. From the terminal, go to server/ folder:
    - run "npm install" to install all the node package
    - Extract the backup_database.tgz
    - run  "mongod --dbpath dump/test"
    - run "mongorestore" to restore the mongoDB dump data for the app.
    - OPTIONAL: run "mongo" to start interaction with the db and check that
    db.products.counts() = 358 and db.categories.counts() = 11 
    - run "node index.js"

======================== Testing the Desktop application =======================
  1. From the terminal, go to web-angular/ folder and run "npm install"
  2. Open chrome browser and go to localhost:3000/web-angular  
  3. Now you can
    - Search for a product(e.g. "cook" to see all the options)
    - Add the product to your cart
    - Login with your facebook account
    - Modify your cart and checkout

======================= Testing Ionic App ======================================
  1. From the terminal, go ionicApp/ folder and run
    - ionic serve --lab. It will open ios and android view in the browser.
      You can copy the link to chrome browser if the trouble with test.
