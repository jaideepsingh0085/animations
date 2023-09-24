# animations
![Screenshot 2023-09-24 230115](https://github.com/jaideepsingh0085/animations/assets/128147644/4d9dad62-7867-4087-bc1e-c7c454e02f94)
![Screenshot 2023-09-24 230122](https://github.com/jaideepsingh0085/animations/assets/128147644/f33decfd-ea1a-4e90-9bb8-900f313a1c21)

Hosted Link : https://jaideepsingh0085.github.io/animations/

HTML :
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the HTML document and specifies the language as English.
<head>: Contains metadata about the HTML document.
<meta charset="UTF-8">: Sets the character encoding to UTF-8 for proper text rendering.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>: Sets the title of the web page displayed in the browser tab.
<link href="./style.css" rel="stylesheet">: Links an external CSS file called "style.css" for styling.
<body>: Contains the visible content of the web page.
<div class="container">: Creates a container or division for grouping elements.
<img src="./watch-1.webp" alt="w-1" height="350" width="350">: Embeds an image with source, alternative text, and specific height and width attributes.
Similar <img> elements for additional images with different source and alt text.

CSS :
*: Selects all elements on the page and applies the following properties.

margin: Sets the margin to zero for all elements.

box-sizing: Sets the box model to "border-box" for all elements.

body: Styles the overall appearance of the web page, including background color and centering content both horizontally and vertically.

background: Sets the background color to black.

display: Uses flex layout for the body, allowing content to be centered.

justify-content: Centers content horizontally.

align-items: Centers content vertically.

min-height: Ensures a minimum height of 100% of the viewport height (100vh).

.container: Styles a container element for images with specific width and a reflective effect.

display: Uses flex layout for the container.

-webkit-box-reflect: Applies a reflective gradient effect below the images.

.container > img: Styles images within the container, specifying max-width, rotation, transition, border-radius, and box shadow.

max-width: Limits the maximum width of images to 350 pixels.

transform-origin: Sets the point of rotation to the center of the images.

transform: Applies a 3D perspective rotation to the images.

transition: Defines a smooth transition effect with a duration of 0.5 seconds.

border-radius: Adds rounded corners to images.

box-shadow: Creates a shadow effect around images.

.container:hover img: Styles images within the container when the container is hovered, reducing opacity.

opacity: Sets the opacity of images to 0.3 when hovered.

.container img:hover: Styles images directly when they are hovered, resetting the rotation and opacity to their default values.
