# I highlighted important points from the course, in my opinion.
This is course about HTML, CSS, SAS, JAVASCRIPT from Udemy website.
Link: https://www.udemy.com/course/build-websites-html-css-sass-javascript/

Important Notes:
If you wanna change width and height not for only content but for entire box then you should use `box-sizing: border-box`. Other box-sizing parameters: `content-box` is for content, `padding-box` is for content+padding, `border-box` is for content+padding+border.

By default div's and other some elements are blocks. So if you wanna make in example 2 div's `inline-block` you should specify them both `inline-box`. Inline element cannot have width and height. In inline-box you should specify width and height.

To modify positioning of inline-blocks you should use: `float: left or right`.

Clearfix is a CSS hack that solves a persistent error that occurs when two floating elements are stacked next to each other. 
Clearfix general form: `.clearfix {
  content: "";
  display: table;
  clear: both;
}`

`Margin(4 parameters): top, right, bottom, left. Margin(2 parameters): top and bottom, right and left.` If you want center element: `margin: top and bottom, auto(for left and right)`.

If browser doesnt support font-family then just specify second one like this: `font-family: Calibri, Arial`.

To make background image fit element fully not stripped down: `background-size: cover`.

If you want to set to child element absolute positioning then you should always set to parent element relative positioning. If you want to child element don't move when scrolling you should use fixed positioning. *Absolute is relative to parent, fixed is relative to window*.

**Section 4: Basics of Web Design**
Fonts and icons:
- Use font size between 15 and 25 pixels for body text
- Font size for headlines - between 32 to 60 pixels
- Reduce font weigh of headlines that are too large. That ensures that the text doesn't steal too much of attention from the rest of the content
- Use line spacing between 120 to 150% of the font size in the body. Decrease line spacing of the large text. So larger line height for smaller text, smaller line height for larger text.
- Traditional font - Serif font. More modern font - Sans Serif font. 
- Use icons to give a more pictorial representation of features or steps
- Try to use icons that are as descriptive as possible
- Try to incorporate icons into call to action buttons and links
- Websites for icons: icomoon, font awesome, flaticon, freepik

Colors:

![image](https://user-images.githubusercontent.com/74294560/177476848-24504f5b-b0ac-4412-a897-52f077e1d228.png)

- Choose your primary and secondary palette colors. 
- Tones: mixing gray to a pure color. Tint: mixing white to a pure color. Shades: mixing black to a pure color.
- Choose accent color. It used to attract attention toward something you want to highlight, like a CTA(call-to-action) button. Use colors that are bolder than you primary colors. It's best if you use a color that contrasts the primary color. Apply these colors to elements like navigation menu, CTAs and other crusial items.
- Use the 60-30-10 rule. This rule helps to have well-balanced webpage. 60% - primary color, 30% - secondary color, 10% - accent color. 60% - negative space, 30% - content, 10% - action elements. 
- Websites for color palette: colorpalette.org, icolorpalette.com, sessions.edu/color-calculator
![image](https://user-images.githubusercontent.com/74294560/177480894-6a394886-c70e-4d9e-a848-280abf395e56.png)
