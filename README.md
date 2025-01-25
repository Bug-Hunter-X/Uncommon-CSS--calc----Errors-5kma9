# Uncommon CSS `calc()` Errors

This repository demonstrates two uncommon errors related to the CSS `calc()` function:

1. **Incorrect `calc()` usage within flexbox:**  When using `calc()` to calculate a width or height within a flexbox context, the calculation might not behave as expected if the parent element's size isn't explicitly set.
2. **Incorrect operator precedence in nested `calc()` expressions:**  Nested `calc()` expressions can lead to unexpected results if operator precedence isn't carefully considered.

The `bug.css` file shows the incorrect implementations, while `bugSolution.css` provides the corrected versions.
