# MongoDB $inc Operator Error
This repository demonstrates an uncommon error when using the `$inc` operator in MongoDB update operations.  The error arises from passing a string value to `$inc` instead of a number. This results in unexpected behavior and potential data corruption.

## Bug
The `bug.js` file contains the erroneous code that attempts to increment a field by a string value.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator, passing a numeric value for incrementing the field.
