# Incorrect use of $inc operator in MongoDB updateOne
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB's `updateOne` method. The `$inc` operator is used to increment a numerical field by a specified value.  However, in this case, we're attempting to increment the 'age' field by a string value ('1'), which leads to an error.

The solution demonstrates the correct way to use `$inc` with a numerical value.