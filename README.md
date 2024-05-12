# Head Pose Estimation using Mediapipe 👤📷

## Description ℹ️
This Python script utilizes the Mediapipe library for head pose estimation in real-time using webcam input. It detects facial landmarks and estimates the head's orientation in terms of pitch, yaw, and roll angles.

## Requirements 🛠️
- Python 3.x
- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)
- NumPy (`pip install numpy`)
- scipy (`pip install scipy`)

## Usage 🚀
1. Run the script in a Python environment.
2. Ensure your webcam is connected and functional.
3. The script will open a window displaying the webcam feed with facial landmark detection and head pose estimation.
4. The head pose will be annotated with text indicating the direction of gaze (e.g., "Looking left", "Looking right") and the current angle of deviation.
5. Press `Esc` to exit the program.

## Features ✨
- Real-time head pose estimation using webcam input.
- Detection of facial landmarks using Mediapipe library.
- Calculation of pitch, yaw, and roll angles to estimate head orientation.
- Visualization of head pose annotations on the webcam feed.

## Notes 📝
- Ensure proper lighting and camera positioning for accurate detection.
- Adjust the thresholds for detection confidence (`min_detection_confidence` and `min_tracking_confidence`) in the script as needed.
- Customize the angle thresholds for defining gaze directions according to your requirements.

## Acknowledgments 🙏
This project was inspired by Mediapipe's FaceMesh and Pose estimation capabilities.

