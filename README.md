# Uncommon HTML Bug: Incorrect innerText Usage

This repository demonstrates a subtle bug related to accessing the text content of an HTML element using `innerText`.  While `innerText` is widely supported, it has had inconsistencies across browsers, particularly in older versions. Using `textContent` is safer and more universally compatible.

## Bug Description

The `bug.html` file shows incorrect usage of `innerText` to obtain the text content of a div element.  In some older browsers or rendering engines, this approach might yield unexpected or incomplete results, particularly when dealing with elements containing nested elements or complex structures.

## Solution

The `bugSolution.html` file provides the corrected solution. Instead of `innerText`, it utilizes `textContent`, which is a more robust and consistent method for retrieving the text content of an element, irrespective of its internal structure or browser version.