### Hand Gesture-Based Drawing Application

This code implements a hand gesture-based drawing application using OpenCV, MediaPipe, and NumPy. It captures hand landmarks from a webcam feed and uses them to draw on a canvas. Users can select different colors and clear the canvas using hand gestures.

#### Key Components

1. **Imports**: Necessary libraries for computer vision and hand tracking.
2. **Color Point Arrays**: Separate arrays to store points for different colors.
3. **Indexes**: Indexes to manage the points in the arrays.
4. **Kernel**: Kernel for dilation purposes.
5. **Colors**: List of colors (Blue, Green, Red, Yellow) and their corresponding indexes.
6. **Canvas Setup**: A blank canvas with buttons for color selection and clearing the canvas.
7. **MediaPipe Initialization**: Setup for hand landmark detection.
8. **Webcam Initialization**: Capture frames from the webcam.
9. **Main Loop**: Processes each frame, detects hand landmarks, handles gestures, and draws on the canvas.

### How to Run

1. **Install Dependencies**:
    ```sh
    pip install opencv-python numpy mediapipe
    ```

2. **Run the Application**:
    ```sh
    python hand_gesture_drawing.py
    ```
