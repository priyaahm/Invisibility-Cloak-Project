Invisibility Cloak using Python and OpenCV

This project demonstrates how to create a simple "invisibility cloak" effect using Python and OpenCV. The effect is inspired by the concept of an invisibility cloak(Not to mention Harry Potter!), where a specific color or background can be hidden or replaced in real-time video, making the object covered by the cloak disappear from view.

Requirements
To run this project, you will need the following:

- Python 3.x
- OpenCV
- NumPy

How It Works
1. Background Capture: The initial background is captured for a few seconds when the cloak is not in view.
2. Color Detection: The color of the cloak is detected using HSV (Hue, Saturation, Value) color space.
3. Masking and Substitution: The detected color is masked and replaced with the previously captured background.
4. Real-time Output: The result is displayed in real-time where the cloak appears invisible.
