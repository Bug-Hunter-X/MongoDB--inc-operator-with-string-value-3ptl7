# MongoDB $inc operator with string value
This code demonstrates an error that can occur when using the `$inc` operator in MongoDB update operations with a string value instead of a number.  The correct usage is to provide a numeric value to the `$inc` operator to increment a field.

## Bug
The `bug.js` file shows an example where `$inc` is used with a string, resulting in an unexpected update or error.

## Solution
The `bugSolution.js` file corrects the code by using a numeric value with the `$inc` operator for a successful update.