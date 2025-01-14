# Off-by-One Error in Java

This repository demonstrates a common off-by-one error in Java array iteration and provides a corrected solution.  The error occurs when the loop condition in `for` loop does not correctly handle the array's upper bound, leading to an `ArrayIndexOutOfBoundsException`.  The solution shows the proper way to iterate through an array and avoid this issue.

## Bug Description
The original code attempts to populate an array with even numbers. However, because of incorrect loop condition, it tries to access an index that does not exist, resulting in a runtime error. 

## Solution
The corrected code adjusts the loop condition to ensure that the iteration stops before reaching the array's maximum index.