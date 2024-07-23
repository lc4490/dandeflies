# Dandeflies

This p5.js sketch creates an interactive visual display where dandelion seeds and butterflies move and react to mouse interactions. It simulates a gentle, dynamic environment with elements that respond to user input.

## How to Use

Open a Web Browser:
Open your preferred web browser and paste this link: https://lc4490.github.io/home/dandeflies/dandeflies.html

## Interact:

Click anywhere on the canvas to start moving the dandelion seeds and butterflies towards the mouse position.
Press the spacebar to reset the sketch and reinitialize the positions of the dandelion seeds and butterflies.
Features

## Dynamic Elements:

Dandelion seeds (Dandefly objects) and butterflies (Butterfly objects) are displayed on the canvas.
Elements respond to mouse clicks and move towards the mouse position.
Interactive Movement:

Seeds and butterflies change their speed and direction based on mouse interactions.
Dandelion seeds have a unique arc-based display, while butterflies have flapping wings.
Visual Appeal:

The background is a soothing light blue, simulating the sky.
The sketch includes a stem and a center for the dandelion, enhancing the visual representation.
Script Overview

setup Function
Initializes the canvas and calls the actualSetUp function to set up the dandelion seeds and butterflies.

keyPressed Function
Resets the setup when the spacebar is pressed.

actualSetUp Function
Populates arrays with Dandefly and Butterfly objects and initializes their positions.

mousePressed Function
Triggers the movement of the dandelion seeds and butterflies based on the mouse position.

draw Function
Continuously updates the canvas, displaying and moving the dandelion seeds and butterflies.

Dandefly Class
Defines the dandelion seed objects, including their display and movement behavior.

Butterfly Class
Defines the butterfly objects, including their display and movement behavior.

## Note

This sketch provides a basic interactive visual display. It may not have extensive error handling or advanced features.

The script runs in the p5.js environment and does not have a graphical user interface (GUI) beyond the canvas.

This application is for educational and entertainment purposes only. It does not involve real money or gambling.

## Disclaimer

This script is provided as-is and may not have full error handling or extensive testing. Use it responsibly and feel free to modify it to suit your needs.

For more information about the script's implementation and behavior, refer to the comments within the script.

**Author**: Leo Chao

**Date**: 2024/07/22
