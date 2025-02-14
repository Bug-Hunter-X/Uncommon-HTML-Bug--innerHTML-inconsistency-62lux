# Uncommon HTML Bug: innerHTML Inconsistency

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML.  Repeatedly using `innerHTML +=` to append multiple elements to an element can lead to unexpected behavior and inconsistencies in the final DOM structure.  This is not a typical error encountered by beginners, but a subtle issue that can occur in more complex scenarios.

The `bug.html` file showcases the bug in action. The `bugSolution.html` file provides a corrected approach using `insertAdjacentHTML` for better DOM manipulation.