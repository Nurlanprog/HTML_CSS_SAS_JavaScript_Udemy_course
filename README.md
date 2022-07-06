# I highlighted important points from the course, in my opinion.
This is course about HTML, CSS, SAS, JAVASCRIPT from Udemy website.
Link: https://www.udemy.com/course/build-websites-html-css-sass-javascript/

Important Notes:
If you wanna change width and height not for only content but for entire box then you should use "box-sizing: border-box". Other box-sizing parameters: "content-box" is for content, `padding-box` is for content+padding, "border-box" is for content+padding+border.

By default div's and other some elements are blocks. So if you wanna make in example 2 div's inline-block you should specify them both inline-box. Inline element cannot have width and height. In inline-box you should specify width and height.

To modify positioning of inline-blocks you should use: float: left or right.

Clearfix is a CSS hack that solves a persistent error that occurs when two floating elements are stacked next to each other. 
Clearfix general form: .clearfix {
  content: "";
  display: table;
  clear: both;
}

Margin(4 parameters): top, right, bottom, left. Margin(2 parameters): top and bottom, right and left. If you want center element: margin: top and bottom, auto(for left and right).

If browser doesnt support font-family then just specify second one like this: font-family: Calibri, Arial.

To make background image fit element fully not stripped down: background-size: cover.

If you want to set to child element absolute positioning then you should always set to parent element relative positioning. If you want to child element don't move when scrolling you should use fixed positioning. Absolute is relative to parent, fixed is relative to window.
