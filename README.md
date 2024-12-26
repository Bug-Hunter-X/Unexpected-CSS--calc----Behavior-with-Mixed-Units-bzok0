# Unexpected CSS `calc()` Behavior with Mixed Units

This repository demonstrates a common issue encountered when using the `calc()` function in CSS: unexpected results when mixing percentage and other units without proper consideration.  The provided `bug.css` file contains the problematic code, while `bugSolution.css` offers the corrected approach.

## Bug Description
The `calc()` function in CSS allows dynamic calculations. However, mixing units incorrectly (e.g., percentages and pixels directly) can lead to unexpected behavior. The original code incorrectly attempts to add a percentage and a percentage, leading to incorrect width calculations.

## Solution
The solution adjusts the `calc()` function to use compatible units.  This ensures accurate width calculations across different viewport sizes.

## How to Reproduce the Bug
1. Open `bug.html` in a web browser.
2. Observe the unexpected width of the element.