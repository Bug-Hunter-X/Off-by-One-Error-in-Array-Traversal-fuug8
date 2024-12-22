# Off-by-One Error in Java

This repository contains a simple Java program that demonstrates a common off-by-one error.  The code attempts to access an array element beyond its valid index range, leading to an `ArrayIndexOutOfBoundsException`. The solution shows how to correct this error.

**Bug:** The `for` loop in the `main` method iterates one time too many, attempting to access `arr[5]` which is out of bounds for an array of length 5 (valid indices are 0 to 4).

**Solution:** The loop condition should be changed to `i < arr.length` to avoid accessing the element beyond the array bounds.