# JavaScript Falsy Value Handling Bug

This repository demonstrates a common JavaScript bug related to the handling of falsy values in a function. The `foo` function is intended to add two numbers, but it only explicitly checks for `null` values.

## Bug Description

The function doesn't correctly handle other falsy values (e.g., `0`, `false`, `undefined`, `""`) as input.  This can lead to unexpected behavior or errors if those values are passed in.

## Solution

The provided solution (`bugSolution.js`) improves the function to handle falsy values more robustly by explicitly checking for the type of the inputs or using a more reliable method for type checking before performing the addition.

## How to run the code:

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your favorite text editor.
3. Run the Javascript code in a browser console or using node.