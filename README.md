# pure-css-mobile-menu -no javascript necessary
Turn a vertical navigation into a horizontal into a responsive mobile slide-down menu with pure css

This project is inspired by navigataur.css (http://mikeking.io/navigataur/) and Tim Pietrusky's 'Advanced Checkbox Hack' (http://timpietrusky.com/advanced-checkbox-hack)

The HTML-File is a a common 3-line layout with header, main container and footer. It shows a centered, fixed width page with a default vertical navigation on the left which turns into a horizontal navigation on breakpoint 1 and a mobile menu on breakpoint 2 that smoothly slides down and up when the menu-button is clicked.

It uses
```css
display: table;
display: table-cell;
```
on the wrapping container (_#main_) and the nav- and content-collumns (_#nav_, _#content_) to achieve switching from vertical to horizontal navigation and Tim Pietrusky's 'Advanced Checkbox Hack' combined with css-transitions for the mobile menu.

~~To avoid any external dependencies i used data-URI for the three-bar mobile menu-button. _(See the image-tag inside the checkbox-label in the nav-container)_~~

For the menu-bar-symbol I used HTML-entity ´&#9776;´. 


You can easily create a data-URI from your own menu-button by using a service like http://dataurl.net.
