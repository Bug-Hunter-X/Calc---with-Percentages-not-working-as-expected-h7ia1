# CSS calc() with Percentages Bug

This repository demonstrates a bug where the `calc()` function in CSS doesn't produce the expected results when used with percentages.  The issue arises when performing calculations involving percentages within the `calc()` function, leading to unexpected layout or styling problems.

## Bug Description

The `calc()` function is designed to allow dynamic calculations within CSS.  However, in this specific scenario, calculations involving percentages yield incorrect values.  This can manifest as elements not being positioned correctly, having unexpected sizes, or other layout anomalies.

## Solution

The solution involves carefully reviewing the calculation and possibly re-examining the approach to achieve the desired layout, potentially using alternative methods like using `vw` and `vh` units.