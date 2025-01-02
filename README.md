# Stack Overflow Bug in JavaScript

This repository demonstrates a common error in JavaScript: stack overflow due to uncontrolled recursion. The `foo` function recursively calls itself without a proper base case for large inputs, leading to exceeding the call stack limit.

The solution involves adding a check to prevent excessive recursion, thus avoiding stack overflow.

## Bug

The `bug.js` file contains the buggy code.  Running it with a large value for 'a' will cause a stack overflow.

## Solution

The `bugSolution.js` file contains the corrected code with iterative approach to avoid stack overflow.