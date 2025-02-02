# Uncommon HTML/JavaScript Bug: Accessing Non-Existent Element

This repository demonstrates a common yet easily overlooked error in web development: attempting to access and modify the properties of an HTML element that hasn't been defined in the HTML structure.  This results in a `TypeError` in JavaScript.

The `bug.html` file contains the erroneous code, while `solution.html` provides the corrected version. This example focuses on the `innerHTML` property, but the same principle applies to other element properties.