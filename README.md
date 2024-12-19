# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java programming error: accessing an array element using an index that is out of bounds.  The `bug.java` file contains code that produces this exception. The corrected version is in `bugSolution.java`.

## Problem:

The original code iterates through an array using a loop condition that goes beyond the valid indices. This leads to an `ArrayIndexOutOfBoundsException` at runtime.

## Solution:

The corrected code in `bugSolution.java` fixes this by using the correct loop condition `i < array.length`, which ensures that the loop only accesses valid indices within the array.

## How to Reproduce:

1. Compile and run `bug.java` to observe the `ArrayIndexOutOfBoundsException`.
2. Compare with and compile and run `bugSolution.java` to see the corrected behavior.