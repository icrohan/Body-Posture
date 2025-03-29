# Body-Posture
Body Posture Detection

This project implements real-time body posture detection using OpenCV and MediaPipe Pose module.

Features

Detects human body posture in real-time using a webcam

Utilizes MediaPipe's Pose module for accurate landmark detection

Draws key body landmarks and connections

Press 'q' to exit the application

Installation

Ensure you have Python installed and install the necessary dependencies:

pip install opencv-python mediapipe

Usage

Clone this repository:

git clone https://github.com/icrohan/body-posture.git
cd body-posture-detection

Run the script:

python body_posture.py

How It Works

Captures video from the webcam.

Converts frames to RGB format for MediaPipe processing.

Detects and tracks body landmarks.

Draws detected pose on the video feed.

Displays the processed video with real-time posture tracking.
