# CSS Float Issue: Undefined Parent Width

This repository demonstrates an uncommon CSS bug related to floating divs and undefined parent container widths.  The bug causes unexpected layout behavior in some browsers, potentially resulting in horizontal overflow.

The `bug.css` file contains the problematic code, while `bugSolution.css` shows a solution using flexbox or other suitable techniques to avoid the issue.

## Bug Description

Floating divs work by taking up only the space necessary to contain their content.  However, when the parent container's width isn't specified, the total width occupied by the floats can exceed 100%, leading to a broken layout.

## Solution

The recommended solution is to use flexbox or grid layout to avoid float-related issues. This approach enables better control over the layout and reduces unexpected behavior across different browsers.