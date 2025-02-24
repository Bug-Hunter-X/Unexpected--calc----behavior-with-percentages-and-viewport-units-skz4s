# Unexpected `calc()` Behavior with Percentages and Viewport Units

This repository demonstrates a bug where the CSS `calc()` function produces unexpected results when combining percentages and viewport units (like `vw` or `vh`).  The expected calculation does not match the rendered output.

## Bug Description

The `calc()` function in CSS is designed to perform calculations. However, when combining percentages and viewport units, the calculation might not be performed as expected, leading to incorrect layout or styling.

## Reproduction

1. Clone this repository.
2. Open `bug.css` and observe the code.
3. Open `bug.html` (or a similar HTML file containing the relevant elements) in a web browser.
4. Note the rendered output and compare it to the expected calculations.

## Solution

The solution, as demonstrated in `bugSolution.css`, involves restructuring the calculation or using alternative approaches, depending on the specific use case.  In many instances, using only percentages or only viewport units will solve the unexpected behavior.