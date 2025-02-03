# :focus-visible Pseudo-class Issue
This repository demonstrates an uncommon issue with the CSS `:focus-visible` pseudo-class.  The problem occurs when the expected keyboard focus outline doesn't appear on a button.  This often arises due to misconfigurations of focus styles, interactions with other CSS rules, or browser inconsistencies.

## Bug Description
The provided CSS code attempts to style the focus outline of a button element using `:focus-visible`.  However, the outline only appears when the button is focused using a mouse, not the keyboard. This is contrary to the intended behavior of `:focus-visible`, which is designed to enhance accessibility by making focus indicators visible only when using assistive technologies or the keyboard.

## Solution
The solution involves ensuring that the `:focus-visible` styles are properly applied and not overridden by other CSS rules. The solution presented here ensures the desired outline only appears on keyboard focus.  See `solution.css` for details.