

# The CSS Box Model

## Topics 
1. Demo of week project : Tweeter
2. Methods of applying CSS
3. CSS Box Model
4. Block and inline property in element
4. HTML5 semantic

## Introduction
In our lecture today, we discussed HTML5 semantic, how to incorporate styles (CSS) into our HTML and the box model. We mentioned that in this week we will lear and use mostly vanilla CSS, Flexbox a powerful CSS library is not in scope for this week. 
We showed a quick demo of the Tweeter app that you will be putting together this week. With the material covered in this lecture, you should be able to jump start your project.

## CSS Box Model
All HTML elements are considered boxes, many of these play the role of containers of other elements, and the way the width and height is calculated in the document becomes even more important. The box model setting determines how browser renders elements on the screen.

## Why is CSS Box Model important?
In order to set width and height of an element correctly in all browsers, and set expectations for sizing elements in the document. By default, the width and height of the content area is set via CSS and the total width and height for its "box" is determined by adding padding and border widths.

Actual visible/rendered width of an element's box = content width + padding + border 

Actual visible/rendered height of an element's box = content height + padding + border 

[Some history about the box model](https://css-tricks.com/box-sizing)
In conclusion, the box model is defined by the box-sizing property:
content-box is the default behaviour (element box dimensions are calculated by adding padding and border value)
border-box is equivalent to IE's “quirks mode" (element's padding & border are included in the box's width & height)

[Demo of the box model](http://guyroutledge.github.io/box-model)

## Block vs inline Elements
Block elements take the whole width of their container, pushing any neighbouring elements down.
Inline elements take only the space that used by their contents, enough to hold itself.
Inline and block element act like block elements but they do not take entire width of the container, allows to set dimensions.
The display property is used to set the block behavior : block, inline, inline-block

## Semantic HTML5
We used this demo to show the use of semantic HTML elements (nav, section, article, main, header) to give proper meaning to different sections it an HTML document and no longer depend on multiple and generic divs that add confusion and lead to time consuming troubleshooting.


  