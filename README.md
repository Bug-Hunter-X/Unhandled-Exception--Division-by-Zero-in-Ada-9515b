# Ada Unhandled Exception: Division by Zero

This repository demonstrates a common error in Ada programming: unhandled exceptions.  Specifically, this example shows a division by zero that lacks proper error handling.

The `bug.ada` file contains the problematic code. The `bugSolution.ada` file shows the corrected version with appropriate exception handling.

## How to Reproduce
1. Compile and run `bug.ada`.  Observe the runtime exception.
2. Compile and run `bugSolution.ada`. Observe the graceful handling of the exception.

## Solution
The solution involves using an exception handler to gracefully manage potential runtime errors, preventing program crashes. 