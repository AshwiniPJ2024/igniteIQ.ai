Drowsiness Detection System

Table of Contents

1. #introduction
2. #requirements
3. #installation
4. #usage
5. #files

Introduction

This is a drowsiness detection system built using OpenCV and Python. The system uses facial landmark detection to track the user's eyes and mouth, and detects drowsiness based on certain thresholds.

Requirements

- Python 3.x
- OpenCV 4.x
- dlib
- shape_predictor_68_landmarks.dat file (download from https://github.com/davisking/dlib-models/blob/master/shape_predictor_68_face_landmarks.dat.bz2)

Installation

Please follow the instructions in the INSTALL.txt file to install the required dependencies.

Usage

1. Run the drowsiness_detection.py script using Python.
2. The system will prompt you to enter the video capture device index (default is 0).
3. The system will start detecting drowsiness and alert you if you appear drowsy.

Files

- drowsiness_detection.py: The main Python script for the drowsiness detection system.
- INSTALL.txt: Installation instructions for the required dependencies.

Note: Please download the shape_predictor_68_landmarks.dat file from the provided link and place it in the same directory as the drowsiness_detection.py script.
