# Voice Control Using Hand Gestures

This project implements a hand gesture-based volume control system using computer vision techniques and the Windows Core Audio API. By detecting hand gestures using OpenCV and a hand tracking module, users can control the volume of their system by simply moving their hand up and down.

# Features:

1. Detects hand gestures using a hand tracking module.
2. Calculates hand area and finger positions to determine the desired volume level.
3. Maps hand movements to volume control using a smooth interpolation algorithm.
4. Provides real-time feedback on the screen, including the current volume percentage and set volume level.
5. Displays frames per second (FPS) for performance monitoring.

# Requirements:
Python 3.x
OpenCV
numpy
pycaw
comtypes


# Usage:
Run the Python script.
Position your hand in front of the camera.
Raise or lower your hand to adjust the volume.
Press 'q' to quit the program.

# Credits:
Hand tracking module: GitHub - OpenAI/hand-tracking: Hand tracking module using OpenCV

# Author:
Rishabh Soni

# License:
This project is licensed under the MIT License.

Feel free to contribute, report issues, or suggest improvements!
