# API Routes

## /api/transaction
* Method: POST
* Mongoose: create
* Index.js Functions: fetch for populateTotal(), populateTable(), populateChart()
* Description: creates single transaction json body

## /api/transaction/bulk
* Method: POST
* Mongoose: insertMany
* db.js Function: checkDatabase()
* Description: Gets multiple transactions in json format after the browser is back online. 

## /api/transaction
* Method: GET
* Mongoose: find({}).sort({date -1})
* Description: Find all transactions in the database and post in order from newest to oldest


## /api/transaction
* Method: DELETE
* Mongoose: remove
* Index.js Functions: ClearButton(), Clear Transactions()
* Description: Delete all the transactions currently stored in the collection.

# HTML Routes

## /
* Home Page

