# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug in HTML related to the usage of `innerHTML` with a JavaScript object.  Attempting to directly assign a JavaScript object to `innerHTML` will result in an unexpected output and might not render the object's properties as expected.

The solution demonstrates the correct approach of stringifying the object or using textContent for a safer output.