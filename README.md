# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `BuggyArraySum.java` file contains code that attempts to sum the elements of an array, but it incorrectly iterates one element beyond the array's bounds, resulting in an `ArrayIndexOutOfBoundsException`.  The corrected version, `CorrectedArraySum.java`, demonstrates the proper way to iterate through an array to avoid this error.

## How to Reproduce

1. Compile `BuggyArraySum.java`.
2. Run the compiled code. You will observe an `ArrayIndexOutOfBoundsException`.
3. Compile and run `CorrectedArraySum.java`. This version will correctly calculate the sum without any exceptions.
