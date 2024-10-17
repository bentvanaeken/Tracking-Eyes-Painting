# Tracking Eyes Painting

## Description

The eyes in the painting follow the viewer as they move. Built with JavaScript the Mediapipe Pose library and TensorFlow's COCO-SSD model, the application tracks the movement of the viewer using a webcam and dynamically updates the position of the eyes on the painting to create a "following eyes" effect. This customizable solution allows you to easily swap out the background, eye images, and adjust the movement settings, making it versatile for different styles and uses. The project is ideal for adding a fun, interactive twist to artwork or portraits.

## Features
- **Eye Tracking**: The eyes in the painting follow the viewer, creating a sense of being watched.
- **Customization Options**: Easily replace the background image, the eye images, or change the positions and offset settings for a tailored experience.
- **Person Detection**: Uses TensorFlow's COCO-SSD to detect if a person is present and adjust eye movement accordingly.
- **Pose Integration**: Uses Mediapipe Pose detection to understand the position of the viewer and guide the eyes accurately.
- **Built with JavaScript**: Easily adaptable and extendable with web technologies.

## Getting Started
To use this project simply clone the repository and host it on a local or remote web server. Ensure you have a webcam connected as the tracking relies on real-time video feed.

## Example Videos

## Installation
1. Clone the repository.
2. Open `index.html` in your browser.
3. Allow access to the webcam when prompted.

## Customization
- **Change the Images**: Replace `achter man.png`, `oogballen.png`, and `man portret.png` in the project folder to use different background, eye, and front images.
- **Adjust Eye Movement**: Tweak the values of `eyeMaxOffsetX`, `eyeMaxOffsetUp`, and `eyeMaxOffsetDown` to control the range of motion for the eyes.

Feel free to experiment with different types of portraits or add your own creative twist to make the experience uniquely yours!

