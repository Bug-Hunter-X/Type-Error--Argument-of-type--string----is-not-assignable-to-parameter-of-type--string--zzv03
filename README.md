# Type Error in TypeScript: Incorrect Argument Type

This repository demonstrates a common TypeScript error: passing an array to a function expecting a single string. The `greeter` function expects a single string, but an array of strings is provided.  The solution shows how to correctly handle this scenario by iterating through the array and calling the function for each string element.  This highlights the importance of type checking and proper argument handling in TypeScript.

## How to Reproduce

1. Clone the repository.
2. Compile the code using the TypeScript compiler (tsc bug.ts).
3. Run the compiled JavaScript code (node bug.js).

You will see a compilation error because of the type mismatch.  The solution shows how to fix this.