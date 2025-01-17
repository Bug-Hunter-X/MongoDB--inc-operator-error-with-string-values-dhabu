# MongoDB $inc Operator Error with String Values

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number.

## Bug Description
The `$inc` operator is used to increment a numeric field in a MongoDB document. If a string value is provided, the operation will fail with an error.

## Bug Reproduction
The `bug.js` file contains code that attempts to increment a field using a string value. This will result in a MongoDB error.

## Solution
The `bugSolution.js` file corrects the issue by providing a numeric value to the `$inc` operator.

## Running the code
1. Ensure you have MongoDB installed and running.
2. Create a collection in your MongoDB database.
3. Run the `bug.js` script to observe the error.
4. Run the `bugSolution.js` script to see the correct usage of the `$inc` operator.
