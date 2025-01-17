# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS selector specificity and the order of rules in a stylesheet.  The bug showcases how different browsers may interpret specificity differently, leading to inconsistent visual results.

## Bug Description
The provided CSS stylesheet contains multiple rules targeting the same HTML element. Due to the complexity of specificity and the order of declaration, the rendered color of the element is not always as expected.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in different web browsers.
3. Observe the color of the target element.  You may see inconsistencies across browsers.

## Solution
The solution involves a careful review of the CSS specificity rules. The solution demonstrates how to correct the rule order and specificity of selectors to ensure consistent visual results across browsers. See `bugSolution.css` for the fixed version.

## Technologies Used
- CSS