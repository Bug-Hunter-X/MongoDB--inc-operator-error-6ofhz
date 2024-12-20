# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation.
The correct usage is to provide a numerical value to increment the field by.  Providing a string will lead to an error.

## Bug
The `bug.js` file contains the erroneous code that attempts to increment a field by a string value.

## Solution
The `bugSolution.js` file shows the correct way to use the `$inc` operator with a numerical value for incrementing the field.
