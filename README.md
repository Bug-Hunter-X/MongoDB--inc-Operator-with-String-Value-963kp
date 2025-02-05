# MongoDB $inc Operator with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The error arises from providing a string value to `$inc` instead of a numeric value.  This results in the counter not being incremented correctly, and can potentially lead to issues with data integrity.

## Bug
The `bug.js` file showcases the incorrect usage of the `$inc` operator with a string value.  This code attempts to increment the `counter` field by 1, but due to the string value, the operation fails as intended.

## Solution
The `bugSolution.js` file presents the corrected implementation. The solution involves ensuring a numerical value is used when updating the counter with the `$inc` operator.
