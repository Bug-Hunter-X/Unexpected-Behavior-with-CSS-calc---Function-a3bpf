# Unexpected Behavior with CSS calc() Function
This repository demonstrates an uncommon error related to the `calc()` function in CSS. The `calc()` function allows for dynamic calculations within your stylesheets, but incorrect usage can lead to unexpected results or errors.

**Problem:**
The original `bug.css` file contains an example where unit incompatibility within a `calc()` expression causes unexpected behavior.  Additionally, a missing space between an operator and value leads to parsing errors.

**Solution:**
The `bugSolution.css` file corrects these issues by ensuring unit compatibility and including proper spacing within the `calc()` expressions. The updated CSS will render correctly.

This example highlights the importance of paying close attention to detail and following best practices when using the `calc()` function in CSS.