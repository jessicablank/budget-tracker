# API Routes

## /api/transaction
* Method: POST
* Mongoose: create
* Description: creates single transaction json body

## /api/transaction/bulk
* Method: POST
* Mongoose: insertMany
* Description: Gets multiple transactions in json format

## /api/transaction
* Method: GET
* Mongoose: find({}).sort({date -1})
* Description: Find all transactions in the database and post in order from newest to oldest

# HTML Routes

## /
* Home Page

