# Type 'string[]' is not assignable to type 'string' in TypeScript

This repository demonstrates a common type error in TypeScript: attempting to pass an array of strings to a function expecting a single string.

## The Bug

The `greeter` function is defined to accept a single string argument and return a greeting. However, the `user` variable is an array of strings.  Calling `greeter` with `user` results in a type error because the function's parameter type doesn't match the argument type.

## The Solution

The solution involves either modifying the `greeter` function to handle arrays or modifying how the `user` variable is used.