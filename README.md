# Incorrect Usage of $inc Operator in MongoDB

This repository demonstrates a common error when using the `$inc` operator in MongoDB: attempting to increment a field with a non-numeric value.

## Bug Description
The `$inc` operator is designed to increment a numeric field by a specified value.  Passing a string value will lead to an error. 

## Bug Reproduction
1. Execute the code in `bug.js`.
2. Observe the error.

## Solution
The solution in `bugSolution.js` corrects the code to use a numeric value for increment.