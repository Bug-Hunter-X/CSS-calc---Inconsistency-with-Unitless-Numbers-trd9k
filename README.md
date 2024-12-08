# CSS calc() Inconsistency with Unitless Numbers

This repository demonstrates an uncommon issue with the CSS `calc()` function when using unitless numbers.  Unitless numbers within `calc()` are not consistently handled across browsers, leading to unexpected results and layout inconsistencies.

The `bug.css` file shows the problematic code. `bugSolution.css` shows the corrected version.  Always include units for numbers within `calc()` to avoid this type of error.

## How to Reproduce
1. Open `bug.html` in your browser.
2. Observe the inconsistent layout.
3. Open `bugSolution.html` and compare the layout.