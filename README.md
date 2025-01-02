# Uncommon HTML Bug: TypeError: Cannot read properties of null (reading 'innerHTML')

This repository demonstrates a common yet easily overlooked error in JavaScript within an HTML context. The error occurs when attempting to access properties of an object that might be null or undefined.

## The Bug
The `bug.html` file contains JavaScript code that tries to manipulate the innerHTML of a div element. However, if the element with the specified ID doesn't exist in the HTML structure, `getElementById` will return `null`, leading to the `TypeError: Cannot read properties of null (reading 'innerHTML')` error.

## The Solution
The `bugSolution.html` file provides a corrected version that adds a null check before accessing the `innerHTML` property, preventing the error.