# CSS Specificity Gotcha: Inheritance and Unexpected Overrides

This repository demonstrates a subtle CSS specificity issue related to inheritance and class selectors.  The bug showcases how unexpected styling can arise from the interaction between inheritance and specificity rules when dealing with nested elements and class selectors.

## Bug Description
The issue involves conflicting styles applied to a paragraph (`<p>`) element nested within a `div` element. Specificity rules and inheritance can lead to unexpected style outcomes that might not be immediately obvious.

## Solution
The solution focuses on clarifying the specificity rules and demonstrating how to achieve the intended styling behavior using more precise selectors or by adjusting the order of CSS rules to manage specificity.