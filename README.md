# Unexpected null return in addition function

This repository demonstrates a common JavaScript bug related to null checks in an addition function.  The function `foo` unexpectedly returns `null` if either of its arguments is `null`, even if the other argument is a valid number. This is a subtle error that can cause unexpected behavior in a program.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version.

## How to reproduce

1. Clone this repository.
2. Open `bug.js` and run it in a JavaScript environment (e.g., Node.js).
3. Observe the unexpected null outputs when calling the function with null parameters.

## Solution

The solution presented in `bugSolution.js` uses a more robust approach to handle null arguments, providing a more sensible and predictable behavior.