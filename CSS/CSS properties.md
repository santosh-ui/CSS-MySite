## icon 
* from favicon.cc

## Display (Property)
* block - block elements takes all the space from left to right on the screen. they won't let other elements sit next to them.
* inline - inline elements takes only the space required for the content to display. they can be placed side by side on the screen.
* inline-block - inline-block elements are same as inline elements but we have control over their size(height x width).
* none - if we set display as none. they will disappear from the screen as they've never been created.

## Position (Property)
* Static - All HTML elements are static by default.
* Relative - It doesn't effect the position of anything else on the screen. It's as if the old position was kept and everything else just flows around it as if it was never moved. It's as if the element left the ghost of itself where it used to be in order for all the other elements to keep their own positions.
* Absolute - It positions the element relative to it's parent. It means that you're adding a margin to its parent element. When using absolute positioning it does affect the flow of your HTML. You're actually taking the element out of the flow of the document and it's no longer considered a part of the natural part of the natural flow of the document. The cool thing is that now I can move the element anywhere on the screen relative to its parent. The element is considered dead.
* Fixed - If an element's position is fixed, if we scroll through the webpage, It will stay in it's current position. This is really useful if you have a "nav bar" that you want to be fixed. Sometimes you have a side bar that you want to stay fixed.

## Coordinates
- we can set values for them in order to determine how we want to move our elements
* top - if we set top property to 20px. the element'll move 20px down.
* bottom - if we set bottom property to 20px. the element'll move 20px up.
* left - if we set left property to 20px. the element'll move 20px right.
* right - if we set right property to 20px. the element'll move 20px left.

## Dark Art of Centering Elements with CSS
* The easiest way of centering the elements is to tap into a property called 'text-align' and that property has to be set inside the parent container(inside top container or the body). // It won't work if we change the width of the block element as it will move to left of the parent container.
* Well the other way of centering the elements is by using margin. So there is a value called "auto" which when applied will center the element either vertically or horizontally. Eg. if we want to center horizontally - margin: (top-bottom)0 (left-right)auto;

## Font-Family
* By default browser will have serif, that gives little feet to sans-serif
* font embedding - head over to fonts.google.com

## Font sizing
* static - px
* dynamic - (%, em) depends on parent's size and applies on top of the parent's size, rem (It refers to the root em) (doesn't depend on parent size, it ignores all of the parent's settings for the font size and just set it relative to the root and applies it's own size.) (the beauty of rem is that it doesn't get effected by upstream size changes and makes it easier to debug when sizing goes wrong.


