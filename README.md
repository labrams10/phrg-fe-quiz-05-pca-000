---
language: css
tags: css, responsive, layout, media queries
type: quiz
resources: 0
---

## Quiz 5 - Positioning, Sprites, & Media Queries

Make a note of your selected answers for the questions below. The correct answers are provided at the end of the quiz along with an explanation.

1. Select the most appropriate CSS declaration to set an element to absolute positioning in the top right corner.  
A.) position: top right;  
B.) position: absolute; top: 0; right: 0;  
C.) position: absolute; top: 0; left: 0;  
D.) None of the above.

2. Fill in the blank: ________ positioning makes an element appear in the same place relative to the browser window even when scrolling occurs.  
A.) absolute  
B.) static  
C.) fixed  
D.) inherent

3. Fill in the blank: Elements with a _________ z-index will appear above other elements.  
A.) lower  
B.) higher  
C.) the same  
D.) negative

4. Fill in the blank: Combining multiple image states into a single graphic image is called a ________ image.  
A.) Sprite  
B.) Pixie  
C.) Combo  
D.) Dwarf

5. Let’s say we have a sprite that is 40 pixels tall showing two event states: a normal state of the icon on top 20 pixels and the hover state of an icon on the lower 20 pixels; Using CSS the sprite is loaded as the background image of an element that is 20px tall and 20px wide. Select the most appropriate CSS declaration to reposition the sprite background image to reveal the lower half (20 pixels) of the hover state icon image.  
A.) background-position: -20px -20px;  
B.) background-position: 0 20px;  
C.) background-position: 20px 0;  
D.) background-position: 0 -20px;

6. True or false: A meta tag with the name of viewport allows us to set the device width, initial scale, and maximum scale, so we can disable zoom in the browser.  
A.) TRUE  
B.) FALSE

7. True or false: We can link to JavaScripts like Google Codes CSS3 media queries fix or modernizer with CSS fix to create compatibility of our media queries in older browsers.  
A.) TRUE  
B.) FALSE 

8. Select the most appropriate CSS media query to change the #wrapper to a 90% fluid width when the screen size is less than or equal to 1024 pixels wide.  
A.) @media only screen and (min-width: 1024px) { #wrapper { width: 90%; } }  
B.) @media only screen and (max-width: 1024px) { #wrapper { width: 90%; } }  
C.) @media all and (min-width: 1024px) { #wrapper { width: 90%; } }  
D.) @media print and (max-width: 1024px) { #wrapper { width: 90%; } }

9. Select the most appropriate CSS media query to change the nav font-size to 1.5 em when the screen size is less than 1024 pixels wide and greater than 480 pixels wide on any type of device.  
A.) @media only screen and (min-width: 1024px) { nav { font-size: 1.5em; } }  
B.) @media (min-width: 481px) and (max-width: 1023px) { nav { font-size: 1.5em; } }  
C.) @media all and (min-width: 480px) and (max-width: 1024px) { nav { font-size: 1.5em; } }  
D.) @media print and (min-width: 480px) and (max-width: 1024px) { nav { font-size: 1.5em; } }

10. Select the most appropriate CSS media query to set the sections to stop floating on screen devices with an available width of 480 pixels or less.  
A.) @media only screen and (max-width: 480px) { section { float: none; } }  
B.) @media (min-width: 480px) { section { float: none; } }  
C.) @media all { section { float: none; } }  
D.) @media only screen and (width: 480px) { section { float: none; } }

## Answer Sheet

1. **B**, Setting an element to position: absolute; allows it to be positioned in relationship to the browser window (or to its relatively positioned parent).  
See video: [Positioning Techniques](http://www.youtube.com/watch?v=gjMBb0jlV8M&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

2. **C**, Setting an element to position: fixed; allows it to stay fixed in place even when the browser window is being scrolled.  
See video: [Positioning Techniques](http://www.youtube.com/watch?v=gjMBb0jlV8M&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

3. **B**, Elements with a higher CSS z-index value (than other elements in the document) will appear (on top) above the other elements. Elements with a lower CSS z-index value will fall below (behind) other elements.  
See video: [Z-Index Layering](http://www.youtube.com/watch?v=0JihpjRE-jM&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

4. **A**, Sprite images can be used to combine multiple image states into a single image. These are most often used in conjunction with CSS code that repositions the sprite during various mouse events such as a:hover. Using a sprite is often more efficient than using several separate images because the sprite loads one time at the beginning of the page being rendered and then is quickly repositioned as needed during user interactions without the need to request additional images from the server.  
See video: [Sprite Rollovers](http://www.youtube.com/watch?v=r38v9W_r5eo&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

5. **D**, The css background-position property accepts two values: the first for horizontal offset and the second for vertical offset. For horizontal offset: positive numbers reposition the image to the right, negative numbers reposition to the left. For vertical offset: positive numbers reposition the image tdownward, negative numbers reposition upward.  
See video: [Sprite Rollovers](http://www.youtube.com/watch?v=r38v9W_r5eo&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

6. **A**, TRUE, <meta name=”viewport” content=”width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0”> helps to disable zooming in the browser.  
See video: [Prep HTML for Responsive Layout](http://www.youtube.com/watch?v=yi_w8h6ahP0&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

7. **A**, TRUE, JavaScript files can be useful for creating additional compatibility support for CSS3 media queries in older browsers.  
See video: [Prep HTML for Responsive Layout](http://www.youtube.com/watch?v=yi_w8h6ahP0&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

8. **B**,@media only screen and (max-width: 1024px) { #wrapper { width: 90%; } }  
See video: [Responsive Layout Techniques](http://www.youtube.com/watch?v=cOpX_la2Rbo&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

9. **C**, @media all and (min-width: 480px) and (max-width: 1024px) { nav { font-size: 1.5em; } }  
See video: [Responsive Layout Techniques](http://www.youtube.com/watch?v=cOpX_la2Rbo&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

10. **A**, @media only screen and (max-width: 480px) { section { float: none; } }  
See video: [Responsive Layout Techniques](http://www.youtube.com/watch?v=cOpX_la2Rbo&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)