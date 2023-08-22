# watch
<h1>Hosted link: - </h1>
https://trishadas13.github.io/watch/?authuser=0
<hr>
![image](https://github.com/trishaDas13/watch/assets/126088849/076cfb32-7670-4b92-88e9-06de3e87db01)
![image](https://github.com/trishaDas13/watch/assets/126088849/0e7f4b22-b3f8-4ab8-98c4-943974acfaba)

Document Type Declaration (<!DOCTYPE html>):

Specifies that the document follows the HTML5 standard.
HTML Start (<html lang="en">):

The root element of the HTML document, specifying the language as English.
Head Section:

Contains metadata and links to external resources.

Character Set (<meta charset="UTF-8" />):

Sets the character encoding to UTF-8.
Viewport Meta (<meta name="viewport" content="width=device-width, initial-scale=1.0" />):

Configures the viewport for responsive design.
Title (<title>animation</title>):

Sets the title of the webpage displayed in the browser's title bar.
Stylesheet Link (<link rel="stylesheet" href="./styles.css" />):

Links an external stylesheet named "styles.css" for styling the content.
Body Section (<body>):

The body of the HTML document where the visible content is placed.
Container (<div class="container">):

A container element to group and organize content.
Cards (<div class="cards">):

A division within the container to hold a set of cards/images.
Images (<img>):

A series of img elements, each representing an image.
The "src" attribute specifies the path to the image file.
The "alt" attribute provides alternative text for accessibility.
HTML End (</body></html>):

Closes the body and HTML elements, ending the document.

![image](https://github.com/trishaDas13/watch/assets/126088849/5f6aa126-3f45-4e97-8aee-82b8d65e1a4e)
![image](https://github.com/trishaDas13/watch/assets/126088849/fa748fca-bc85-45cc-b2d9-7d71df74e587)

I've used the universal selector * to reset margins, paddings, and ensure that the box sizing is border-box, which prevents padding and border from affecting the element's width and height.

The .container class styles the main container for the cards. It occupies the full width and height of the viewport (100vh). The content is centered both horizontally and vertically using display: flex, justify-content: center, and align-items: center. The background color is set to black.

The .cards class styles a container for the cards themselves. It uses display: flex to arrange the cards in a row and justify-content: space-between to create even spacing between them. The -webkit-box-reflect property adds a reflective gradient below the cards to create a subtle reflection effect.

The img selector styles the images within the cards. Images have fixed dimensions of 350px by 350px and a border radius of 10px. A box shadow is applied to give a subtle shadow effect, and the images are rotated around their vertical axis using the transform property to create a 3D-like perspective.

The transition property is applied to the images to create a smooth transition effect when properties change. When hovering over the .cards container, the opacity of the images is reduced to 0.3 using opacity: 0.3.

Additionally, when hovering over individual images, their rotation is reset to its initial state (rotateY(0deg)) and opacity is set to 1, providing an interactive 3D-like effect as the images appear to flip back to their original position on hover.

This code sets the foundation for a visually appealing interactive card layout with hover effects. You can customize it further by adding more styles and content to suit your design preferences.
