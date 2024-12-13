# Uncommon HTML Bug: DOM Element Access Typo

This repository demonstrates a subtle but common bug in HTML/JavaScript involving a typo in accessing a DOM element using `document.getElementByIdx` instead of the correct `document.getElementById`.

The bug is simple to reproduce and highlights the importance of careful coding and thorough testing.

## Bug Description:
The provided HTML file contains a JavaScript script that attempts to modify the content of a div element.  A simple typo in `getElementByIdx` prevents the script from finding the element, resulting in no changes and a silent failure.

## Solution:
The solution file corrects the typo, making the script correctly access and modify the div element.