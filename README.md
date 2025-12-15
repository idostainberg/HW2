Overview

This is a small front-end project demonstrating a responsive grid layout. The layout is implemented using a custom float-based CSS grid system (part1.css), with media queries to adapt the structure for mobile screens.
The main purpose of the project is to showcase various CSS techniques for creating flexible and complex layouts, with alternatives provided for comparison (Flexbox and a more modern approach).

Project Structure
File Name,Description
part1.html - The main HTML structure defining the layout using custom col- classes.
part1.css - The original float-based CSS grid system and responsive styles.
part2A.css - "An alternative, modern float-based CSS using CSS Variables and a display: table technique for equal column heights."
part2B-flex.css - An alternative implementation using Flexbox to achieve the same layout.
part1new.html - An example of how this layout could be implemented using Bootstrap 5.
part2c.css - Minimal styling used with part1new.html.

Layout Details
A narrow left column (.col-1 .left).
A wide right frame (.col-11 .right-frame) containing nested grid elements.


Responsiveness
The default (desktop) layout is the two-column structure. At a viewport width of 750px or less, the following changes occur (as defined in part1.css):

The left column (.col-1) and the right frame (.col-11) switch to full width (100%) and stack vertically.

All nested columns within the right frame (.col-3, .col-4, .col-8) also switch to full width (100%) and stack vertically.

All content boxes maintain a consistent minimum height of 70px for a uniform mobile look

