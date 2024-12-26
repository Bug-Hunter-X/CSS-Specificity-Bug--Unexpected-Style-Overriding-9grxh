# CSS Specificity Bug: Unexpected Style Overriding

This repository demonstrates a common CSS issue related to selector specificity.  The problem arises when a more specific selector (in this case, an ID selector) unintentionally overrides the styles applied by a less specific selector (a class selector).

The `bug.css` file contains the problematic CSS, while `solution.css` provides a corrected version.

## Problem
The `#outer` div is intended to have a lightblue background.  However, due to the specificity of the ID selector, the `inner` div's `lightcoral` background overrides it, resulting in an unexpected visual output.

## Solution
The solution involves carefully considering selector specificity and making adjustments to ensure the intended styling is applied correctly.
This might involve using more specific selectors to target the inner div's background or rethinking the CSS structure. 