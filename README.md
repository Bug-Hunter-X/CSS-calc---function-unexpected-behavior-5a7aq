# CSS calc() Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS. The `calc()` function is powerful for dynamic calculations, but inconsistencies in units or browser compatibility can lead to unexpected results.

## Bug
The example `bug.css` showcases a scenario where `calc()` doesn't produce the expected outcome due to a missing unit or unsupported calculation.  This can often result in the element not rendering as anticipated.

## Solution
The `bugSolution.css` file provides the corrected CSS, ensuring consistent units and addressing potential browser incompatibility issues.

## How to reproduce the bug
1.  Create an HTML file and include the `bug.css` stylesheet.
2.  Observe that the element with the `calc()` width does not render as expected.

## How to solve the bug
1.  Replace `bug.css` with `bugSolution.css`.
2.  Observe that the element now renders correctly.