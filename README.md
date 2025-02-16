# Missing Semicolon in Express.js Route Handler

This repository demonstrates a common yet subtle error in Express.js route handlers: a missing semicolon.  This seemingly minor omission can lead to unexpected behavior and difficult-to-debug issues.

The `bug.js` file contains the erroneous code.  The `bugSolution.js` file provides the corrected version.

## Bug

A missing semicolon after the `return` statement in the error handling block can lead to unintended code execution.

## Solution

Adding the semicolon fixes the issue, ensuring the correct response is sent if a user is not found.