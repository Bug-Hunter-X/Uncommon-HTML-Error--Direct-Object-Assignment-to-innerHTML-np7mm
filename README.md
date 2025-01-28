# Uncommon HTML Error: Direct Object Assignment to innerHTML

This repository demonstrates an uncommon error in HTML related to the use of `innerHTML`.  The `innerHTML` property expects a string value; however, attempting to assign a JavaScript object directly results in an error and unexpected behavior.

The `bug.html` file contains the erroneous code, while `bugSolution.html` provides the corrected version.

## Error Description

The error occurs because `innerHTML` cannot directly interpret a JavaScript object.  It requires a string that represents the HTML content. Attempting to assign an object results in the object being converted to `[object Object]` in the browser, which is not a valid HTML structure.