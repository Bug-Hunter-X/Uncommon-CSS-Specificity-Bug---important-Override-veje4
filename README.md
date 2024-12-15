# Uncommon CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity and the `!important` declaration. The bug highlights an unusual interaction where a highly specific selector overrides a selector with `!important` due to its higher specificity.

## Bug Description

The `bug.css` file contains CSS rules that illustrate the unexpected behavior.  The `!important` declaration is intended to force a specific font size, but it is unexpectedly overridden by another selector with higher specificity.

## Solution

The `bugSolution.css` file offers a solution to avoid this situation by carefully managing selector specificity or finding a different approach to achieve desired styles without unnecessary reliance on `!important`.