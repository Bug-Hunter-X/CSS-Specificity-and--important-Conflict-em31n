# CSS Specificity and !important Conflict

This repository demonstrates a subtle bug involving the interaction between CSS specificity and the `!important` declaration.  The bug arises when a highly specific selector takes precedence over a rule marked as `!important`. This is counter-intuitive to developers who expect `!important` to always win.  The example code shows how this can lead to unexpected styling changes.

The solution provided prioritizes specificity over `!important` by refactoring the CSS to remove unnecessary use of `!important` and employing well-structured selectors.

## How to reproduce

1. Clone this repository.
2. Open `bug.css` to see the buggy code and observe the unexpected behavior in the browser.
3. Open `bugSolution.css` to see how the issue is resolved.

This example highlights the importance of careful CSS structure and avoiding excessive use of `!important` for maintaining maintainable and predictable styles.