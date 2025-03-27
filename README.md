Motion2Human

Motion2Human is a motion-controlled game that uses OpenCV and MediaPipe for real-time human pose detection. The game simulates the experience of playing Temple Run using body movements detected through a webcam.

Features

Pose Detection: Uses MediaPipe to identify key body points.

Gesture Control: Detects movements like jumping, crouching, and side-stepping to control in-game actions.

Real-time Processing: Uses OpenCV for webcam input and real-time movement tracking

Technologies Used

Python - Core programming language

OpenCV - For real-time webcam input and image processing

MediaPipe - For human pose detection

NumPy - For numerical computations and data handling

Features

Pose Detection: Uses MediaPipe to identify key body points.

Gesture Control: Detects movements like jumping, crouching, and side-stepping to control in-game actions.

Real-time Processing: Uses OpenCV for webcam input and real-time movement tracking.

How It Works

Detects Body Movements:

Uses myPose.py to analyze real-time webcam input.

Recognizes gestures such as jumping, crouching, and left/right movements.

Maps Movements to Actions:

Jump → Character jumps

Crouch → Character slides

Left/Right Lean → Character moves left/right

Runs the Game:

The player moves continuously, and the user must avoid obstacles using body movements.

Future Enhancements

Improve movement accuracy with additional body landmarks.

Add gesture-based menu navigation.

Enhance UI and game mechanics for better user experience.

Contributing

Feel free to fork the repository and submit pull requests for improvements!
