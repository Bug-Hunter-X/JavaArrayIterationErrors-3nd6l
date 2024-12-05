# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs when the loop's termination condition is incorrect, leading to an attempt to access an index outside the array's bounds. This results in an `ArrayIndexOutOfBoundsException`.

The `BuggyArray.java` file shows the code with the error. The `CorrectedArray.java` file provides the corrected version.

## How to Run

1. Clone this repository.
2. Compile the Java files: `javac BuggyArray.java CorrectedArray.java`
3. Run the buggy code: `java BuggyArray` (Observe the exception)
4. Run the corrected code: `java CorrectedArray` (Observe the correct output)

This example highlights the importance of carefully considering loop termination conditions when working with arrays.