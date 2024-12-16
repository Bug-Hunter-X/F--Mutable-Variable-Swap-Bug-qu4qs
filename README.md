# F# Mutable Variable Swap Bug

This repository demonstrates a common bug in F# related to mutable variables and function arguments.  The `swap` function attempts to swap two mutable integer variables, but due to pass-by-value semantics, it fails to modify the original variables.

The `bug.fs` file contains the buggy code, while `bugSolution.fs` provides a corrected version using techniques to modify variables outside the scope of the function. 

This example highlights the importance of understanding how F# handles mutability and variable scope.