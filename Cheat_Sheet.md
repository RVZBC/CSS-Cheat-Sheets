CSS Cheat Sheet

Reference:
*https://www.w3schools.com/cssref/css_selectors.asp
*https://css-tricks.com/almanac/
*https://css-diner.netlify.app/
*https://elementor.com/help/whats-the-difference-between-px-em-rem-vw-and-vh/

Cascading Style Sheets at the most basic level it indicated that the order of CSS rules matter. Sorted from least important to most important

.class
#id
* => all elements
element
element1, element2 => Select element 1 and element 2 to have both properties
element1 ~ element2 => Select the elements that is exactly after element1
element1 element2 => Select all element 2 that is inside element 1
element1 > element2 => Select all elements that has a parent element 1
element1 + element2 => Select an element that is exactly after element 1
:hover
:last-child
:first-child
!important (not recommended)


other CSS selectors
:nth-child() => Select an element by its order in another element

:nth-last-child() => Select an element by its order in another element, counting from the back

:first-of-type => Select the first element of a specific type

:nth-of-type(A) => Selects a specific element based on its type and order in another element - or even or odd instances of that element. input inside the parenthesis can be number or (odd or even).

:nth-of-type(An + B) =>The nth-of-type formula selects every nth element, starting the count at a specific instance of that element.

:only-of-type => Select elements that are the only ones of their type within their parent element

:last-of-type => Select the last element of a specific type

CSS wild card selectors
element[attribute] => Select an element with a specific attribute

element[attribute^="Sel"] => Select an element with an attribute value that starts with "Sel"

element[attribute*="Sel"] => Select an element with an attribute value that contains "Sel" anywhere

element[attribute$="Sel"] => Select an element with an attribute value that ends with "Sel"


What selectors win out in the cascade depends on:
-Specificity
-Importance
-Source order

PX, EM, REM, %, VW, and VH

Absolute Units

PX =>  Pixels (px) are considered absolute units, although they are relative to the DPI and resolution of the viewing device. But on the device itself, the PX unit is fixed and does not change based on any other element. Using PX can be problematic for responsive sites, but they are useful for maintaining consistent sizing for some elements. If you have elements that should not be resized, then using PX is a good choice.

Relative units
    Font Sizing Units
        EM => Relative to the parent element
        REM => Relative to the root element (HTML tag)
    
    For margins, padding, spacing, and widths/heights
        %: Relative to the parent element
        VW: Relative to the viewport's width
        VH: Relative to the viewport's height

