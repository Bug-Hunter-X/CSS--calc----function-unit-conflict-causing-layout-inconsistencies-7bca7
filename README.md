# CSS `calc()` Function Unit Conflict

This repository demonstrates an uncommon error related to the usage of the `calc()` function in CSS. The issue arises from inconsistent unit usage within the `calc()` function, specifically when subtracting pixel values from percentages.

## Bug Description
The bug occurs when using pixel values (`px`) alongside percentages (%) in the `calc()` function. This combination can lead to unpredictable results depending on the browser and the context. 

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to see the problematic code.
3. Open `bugSolution.css` to see a corrected version of the code. 
4. Observe the differences in rendering behavior.

## Solution
The solution involves maintaining unit consistency within the `calc()` function. One way to address this is to ensure all units used in the calculation are either percentage values or pixel values.