# MongoDB $inc operator error with string value
This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update queries.  The error occurs when you provide a string value to the `$inc` operator, which is designed to increment numeric fields. The incorrect usage will not update the field and may throw an error depending on the driver and version.

## Problem
Incorrect usage of `$inc` with a string value will not increment the field and may result in unexpected output.

## Solution
Ensure you use a numeric value (integer or float) with the `$inc` operator.  The provided solution shows the corrected update operation with an integer value.
