# JavaScript Strict Equality Bug

This repository demonstrates a common but subtle bug in JavaScript related to the strict equality operator (`===`). The `foo` function is intended to check if two values are equal, but it fails to do so correctly.  The provided solution explains the bug and how to fix it.

## Bug

The `bug.js` file contains the buggy function. This function always returns `false`, even if both arguments are equal.

## Solution

The `bugSolution.js` file contains the corrected function.  This fix removes the unnecessary `else` statement and directly returns the boolean result of the equality check. It uses a more efficient comparison method. 
