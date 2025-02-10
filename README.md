# CSS Specificity Bug

This repository demonstrates a common issue in CSS related to selector specificity. The bug showcases how a more specific selector can unexpectedly override a less specific selector, even if it's defined later in the stylesheet.

## Bug Description
The primary issue lies in understanding how CSS resolves conflicting style declarations.  A selector's specificity determines its precedence. More specific selectors override less specific ones. This can lead to unexpected results if not carefully considered. 

The solution provided modifies the CSS to ensure that styles are applied as intended. 

## Setup
1. Clone this repository.
2. Open `bug.html` (or create your own HTML) in your web browser. Note that the text color is blue, not the expected red due to higher specificity of the `#myDiv p` rule.
3. Open `bugSolution.html` (or create your own HTML) in your web browser. Note the text color changed to red after CSS selector improvements.

## Solution
Examine `bugSolution.css` to see the corrected CSS.