# Incorrect Handling of NaN Values in foo() Function

This repository demonstrates a common error in JavaScript: the incorrect handling of NaN (Not a Number) values.

The `foo()` function is designed to handle null, negative, and positive numbers. However, it does not explicitly check for `NaN`, leading to unexpected behavior. 

The bug is demonstrated in `bug.js`.  The solution, which handles NaN values appropriately, is shown in `bugSolution.js`.

This example highlights the importance of robust input validation in JavaScript functions.  Always consider edge cases such as `NaN`, `Infinity`, and `-Infinity` to prevent unexpected errors in your applications.