# CSS Calc() Error: Unexpected Calculation Results

This repository demonstrates a common yet subtle error involving the CSS `calc()` function.  The error arises from issues with operator precedence, missing spaces, or incompatible units within the calculation. This can lead to unexpected and unpredictable layout results.

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

## Bug Description
The `calc()` function's result is not what is expected due to incorrect calculation. This frequently happens because of:

* **Operator Precedence:** Incorrect interpretation of the order of operations.
* **Missing Spaces:**  Forgetting spaces between operators and values is a frequent source of errors.
* **Incompatible Units:** Combining units in a way that `calc()` cannot handle.

Understanding these potential issues is essential to writing robust and predictable CSS.