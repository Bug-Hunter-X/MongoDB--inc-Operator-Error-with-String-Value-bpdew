# MongoDB $inc Operator Error with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error arises when attempting to increment a numeric field with a string value. The solution involves ensuring the value used with `$inc` is a number.

## Bug
The `bug.js` file contains code that attempts to increment the `age` field with a string value, which results in an error.

## Solution
The `bugSolution.js` file shows the corrected code, where the increment value is now a number, resolving the error.
