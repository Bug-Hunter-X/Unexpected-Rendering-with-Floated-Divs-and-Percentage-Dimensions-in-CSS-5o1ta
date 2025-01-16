# Unexpected Rendering with Floated Divs and Percentage Dimensions in CSS

This repository demonstrates an uncommon rendering issue in CSS related to floated `div` elements with percentage-based width and height values.  Certain browsers may incorrectly calculate these dimensions, resulting in unexpected layout behavior.

## Problem

The provided CSS causes inconsistent rendering across different browsers. The percentage values for width and height might not be interpreted consistently, particularly when `float: left` is applied.

## Solution

The solution involves using a different approach to achieve the desired layout, avoiding percentage-based height for floated elements.  Consider using a flexbox or grid layout for better cross-browser consistency.

## Reproduction

1. Clone this repository.
2. Open `bug.html` in various browsers.
3. Observe the differences in rendering.