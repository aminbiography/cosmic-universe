Live URL:  https://aminbiography.github.io/cosmic-universe/



#<h1>This code is a creative HTML and CSS design that simulates a "cosmic universe" environment with interactive and animated elements like stars, galaxies, and an Earth-like container.
<br>
Below is a detailed description for developers:</h1>

# <h2>HTML Structure
<br>
HTML Boilerplate:</h2>

Includes the <!DOCTYPE html> declaration for HTML5.
Specifies the lang attribute as en for English.
Meta tags for character encoding (UTF-8) and viewport responsiveness for mobile-friendly design.
Background Layers:

Stars Background (.stars): A full-screen div with an animated starry background using a background image.
Twinkling Stars (.twinkle): A layer containing dynamically placed stars and pentagon-shaped "stars" (created with clip-path: polygon).
Galaxies (.galaxyN):

Multiple circular div elements (galaxy1, galaxy2, etc.) represent spinning galaxies, positioned at various areas of the screen.
These use a background image and rotate indefinitely with the rotateGalaxy keyframe animation.
Rotating Earth-like Container (.container):

A circular div that mimics an Earth-like appearance using layered radial gradients.
It rotates continuously using CSS animations (rotateAnimation) and has a shadow for depth.


# <h2>CSS Description
<br>
Global Styling:</h2>

Resets margins and paddings for the body, h1, and p elements to ensure consistent rendering across browsers.
The body element is styled as a dark background (#0a0a0a) with white text, centered content using Flexbox, and hidden overflow.
Stars Background (.stars):

Positioned absolutely to cover the entire screen (width: 100%; height: 100%;).
Utilizes a background image (url) with a smooth animation (starryBackground) to simulate moving stars.
Twinkling Stars (.twinkle and .star):

Stars are positioned absolutely with a circular shape (border-radius: 50%;).
The pentagon-shaped stars use clip-path: polygon to create the geometric shapes.
Both types of stars fade in and out with the twinkling animation (changes in opacity).
Galaxies (.galaxy1, .galaxy2, etc.):

Circular divs with a galaxy texture applied via background: url.
Positioned in different areas of the screen using absolute coordinates (top, left, bottom, right).
Animated to rotate indefinitely using the rotateGalaxy keyframe animation.
Earth-like Container (.container):

Styled as a circular, rotating div with layered gradients that simulate landmasses and oceans.
Uses radial-gradient for layered coloring (green for land, blue for ocean).
A shadow (box-shadow) is applied for a glowing effect.
Animates a full 360-degree rotation using rotateAnimation.
Keyframe Animations
starryBackground:

Animates the starry background to simulate a moving cosmic effect.
twinkling:

Creates the twinkling effect by changing the opacity of stars.
rotateGalaxy:

Rotates each galaxy div indefinitely in a clockwise direction.
rotateAnimation:

Rotates the Earth-like container in a smooth, infinite 360-degree loop.
Key Features
Dynamic Elements:

Stars and galaxies are positioned dynamically and can be easily adjusted for density or placement.
Reusability with predefined galaxy and star shapes.
Responsive Design:

The viewport meta tag and percentage-based positioning ensure compatibility with different screen sizes.
Aesthetic Animation:

Layered animations create depth and simulate a realistic universe.
Interactive Visual Appeal:

Use of gradients, shadows, and animations provides an engaging cosmic theme.

<p>Usage Suggestions</p>
Suitable for landing pages, interactive backgrounds, or creative portfolio sections.
Developers can adjust the galaxy and star positions, sizes, and animations for a customized appearance.
Replace the provided background images (url) with different textures for varied cosmic effects.
