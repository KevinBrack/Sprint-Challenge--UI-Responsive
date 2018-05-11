<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

box3

2. Describe the difference between `display: block;` and `display: inline;`.

`display: block` on an HTML element will reserve the width of the entire document or container to display the item. `display-inline` will not reserve extra space allowing other HTML elements to display on the same vertical start point.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

The cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Adaptive layout uses breakpoints in the css file to alter the layout depending on the size of the viewport or size of the viewing device.

Fixed layout has hard coded widths. It will display the same width regardless of the viewport it is in.

Fluid layout uses percents only for the width. It scales to the size of the viewport at all times, but it does not alter the layout when the window is resised or viewed on moble devices.

Responsive layout uses a combination of CSS breakpoints and percent based with to not only scale but adapt the layout depending on the size of the viewport or device it is viewed on.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Without `max-width` on the outermost container, the content would spread out on the horizontal axis beyond our design intentions. A text element for example could stretch far beyond the recommended 500 pixel width, and user concentration could be affected.