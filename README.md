# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (==). Loose equality can lead to unexpected type coercion and errors that are difficult to debug.

## The Bug
The bug lies in how JavaScript handles loose equality comparisons.  It attempts to coerce values to the same type before comparison, leading to unexpected results when comparing against null.

## The Solution
The solution is to use strict equality (===) for comparisons to prevent type coercion. Strict equality checks for both value and type, leading to more predictable and reliable results.

## How to Reproduce
1. Clone this repository.
2. Run `bug.js` (demonstrates the issue). 
3. Run `bugSolution.js` (shows the fix).