# Uncommon HTML Nesting Error

This repository demonstrates a common yet easily overlooked HTML error: incorrect nesting of elements.  Improper nesting can lead to unexpected rendering and validation issues, especially when dealing with complex layouts.

## The Bug
The `bug.html` file contains an example of incorrect element nesting, specifically an improperly nested &lt;div&gt; element within an &lt;ul&gt; element. This is semantically incorrect and may cause rendering problems across various browsers.

## The Solution
The `bugSolution.html` file shows the corrected version, where the &lt;div&gt; element is properly nested outside the &lt;ul&gt; element. This restores the semantic validity and improves the consistency of the rendered HTML.

## How to reproduce the bug:
1. Open `bug.html` in a web browser.
2. Inspect the rendered HTML using your browser's developer tools to observe the unexpected rendering or validation errors. 

## How to fix the bug:
1. Open `bugSolution.html`
2. Inspect the corrected code to observe the proper nesting and corrected rendering.