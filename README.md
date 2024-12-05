# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value.  However, attempting to increment with a non-numeric value will result in an error.

**bug.js** showcases the incorrect usage, while **bugSolution.js** provides the correct implementation.

This example highlights the importance of ensuring data types are correct when interacting with MongoDB.