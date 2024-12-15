# Uncommon HTML Bug: Assigning Non-Existent Properties

This repository demonstrates an uncommon HTML bug related to assigning non-existent properties to HTML elements. While not always immediately causing errors, this practice can lead to unexpected behavior and inconsistencies across different browsers.

## Bug Description
The bug involves attempting to add a property to an HTML element that is not a standard or defined property of that element type.  Modern browsers might allow this assignment without throwing an error; however, attempting to access this newly added property later may be unreliable or cause silent failures.

## How to Reproduce
1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Observe the console output.  You might see `undefined` where you would expect 'hello'.

## Solution
The solution demonstrates the correct way to handle element properties and attributes to avoid the error.  The solution uses standard methods for accessing and manipulating element properties.