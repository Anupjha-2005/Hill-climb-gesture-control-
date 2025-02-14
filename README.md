Gesture Control Game is an innovative project that allows users to control in-game actions using hand gestures detected by a webcam. By leveraging technologies like OpenCV, MediaPipe, and PyAutoGUI, this project enables interaction with games or applications based on finger movement and gestures.

Key Features:
Hand Gesture Recognition: Uses MediaPipe's hand tracking solution to recognize and track the movement of fingers.

Control the Game with Gestures: Simulate keyboard inputs (e.g., acceleration, braking) based on the number of fingers raised:

5 fingers raised: Accelerate (right arrow key)

0 fingers raised: Brake (left arrow key)

1 finger raised: Move the cursor based on the index finger position.

2 fingers raised: Simulate a mouse click.


Real-time Performance: 

Detects hand gestures and translates them into real-time actions in the game.
Technologies Used:
OpenCV: For webcam video capture and image processing.
MediaPipe: For hand tracking and gesture recognition.
PyAutoGUI: For controlling the mouse and keyboard based on gestures.

Usage Instructions:


Ensure your webcam is connected and functional.

Start the script and follow the on-screen instructions.

5 fingers for accelerating, 0 fingers for braking.

1 finger to move the cursor and 2 fingers to simulate a click.

Prerequisites:


Python 3.x

OpenCV

MediaPipe

PyAutoGUI

Future Improvements:


More complex gesture support (e.g., zoom, rotate).

Better performance tuning for smoother control.

Integration with more games and applications.
