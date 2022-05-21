# css-art
This project exists as a way for me to practice various techniques to create graphics and animations using CSS. 

In order to view the art, the CSS file must first be linked to an HTML file in order to be viewed. CSS files that do not have a corresponding HTML file use \_template.html

This requires you to update the href in \_template.html to the reference the CSS file that you want to view.

## template
These files exist as initial setup to save me time when starting a new piece. Some simple graphics do not require any changes from the \_template.html file and as such, those graphics do not have their own HTML files. See the main header section for more detail.

\_template.css contains centered red square with several commonly-used properties initialized to 0.

## mario
mario.css contains a single 10x10 transparent square with over 150 box-shadows. Each box-shadow is offset in increments of 10 pixels and has no blur and no spread radius, making them identical copies of the original square but with a new position and color. This creates a square grid that mimics that appearance of pixel art. I used this technique to recreate the default Mario sprite from Super Mario Bros (© 1983 Nintendo) for the NES. 

This technique was rather laborious even for a small, simple piece. Similar results could be achieved by using new html elements to create larger rectangles for areas that a predominantly a single color. The hat, for example, could be a 50x10 rectangle with a 90x10 rectangle underneath, creating a nearly-identical image with a fraction of the work. However, for a more complex pixel art piece that uses gradient-like shading and has little-to-no areas of contiguous color, this technique is effective.
