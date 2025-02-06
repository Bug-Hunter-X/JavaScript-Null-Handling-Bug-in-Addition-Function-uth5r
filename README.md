# JavaScript Null Handling Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to handling null values in arithmetic operations. The `foo` function is designed to add two numbers; however, it prematurely returns 0 if either input is null. This behavior might not always be the desired outcome.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version that gracefully handles null values.

## Bug Description

The `foo` function directly returns 0 if either of its arguments is null, which might lead to unexpected results. A more appropriate approach would be to either use a default value (like 0) or throw an error, depending on the intended function behavior.

## Solution

The solution demonstrates a refined version of the function, which uses a default value in case of null inputs.