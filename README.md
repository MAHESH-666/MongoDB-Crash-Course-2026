# MongoDB Crash Course — Practice Scripts

A small collection of MongoDB shell scripts organized by common CRUD and database concepts. The numbered filenames suggest a recommended learning sequence.

## Topics

1. `01_setup.mongodb.js` — initial database/collection setup
2. `02_reading.mongodb.js` — read/query operations
3. `03_update.mongodb.js` — update operations
4. `04_delete.mongodb.js` — delete operations
5. `05_aggregation.mongodb.js` — aggregation pipeline practice
6. `06_indexes.mongodb.js` — indexes

## Requirements

- MongoDB Server or MongoDB Atlas test database
- MongoDB Shell (`mongosh`) or a compatible MongoDB development tool

## How to use

1. Connect to a disposable practice database.
2. Open the scripts in order and review the selected database and collection names.
3. Execute one script at a time and inspect the results.
4. Use test data; do not run delete/update examples against production data.

For shell execution, connect with `mongosh` first and run the commands from the relevant script. Adjust database and collection names to match your environment.

## Learning goals

Practice query filters, sorting/projection, document updates/deletes, aggregation stages, and index creation. Add example documents and expected output as the lessons grow.
