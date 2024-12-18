# Unexpected Early Exit in TypeScript Loop

This example demonstrates a common error in TypeScript loops where an early exit condition within the loop can lead to unexpected results.  The `printNumbers2` function intends to print numbers up to 'n', but the `return` statement within the loop causes premature termination when `i` reaches 3. The goal is to illustrate this unexpected behavior and provide a corrected solution.

## How to Reproduce

1.  Clone this repository.
2.  Compile and run the `bug.ts` file using a TypeScript compiler (tsc) and Node.js.
3.  Observe that the output differs from the expected behavior.

## Solution

The solution is provided in `bugSolution.ts`. It demonstrates how to modify the function to achieve the intended behavior by removing the premature `return` statement or using alternative approaches such as a `while` loop with a conditional flag.