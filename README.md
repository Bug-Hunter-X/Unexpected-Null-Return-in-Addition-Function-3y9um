# Unexpected Null Return in Addition Function

This repository demonstrates a common error in JavaScript functions: unexpected null returns.  The `foo` function adds two numbers but returns `null` if either input is `null`. This can cause problems if calling functions don't explicitly handle null values.  The solution demonstrates how to improve the function to handle null inputs more gracefully.

## Bug

The `bug.js` file shows the function with the bug.  The function returns `null` even if one input is a number. This may cause issues in other parts of your code.

## Solution

The `bugSolution.js` file provides a corrected version. Instead of returning null, it returns 0 or the only provided value.