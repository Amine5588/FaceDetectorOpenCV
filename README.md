# Real-time-face-detection-using-Python-and-OpenCV

Face Recognition using OpenCV
This Python script helps in identifying faces using the OpenCV library. It uses a Haar Cascade classifier for face detection and creates a model to recognize faces captured through the camera stream.

Requirements
Python 3
OpenCV library
NumPy
Usage
Ensure you have the necessary libraries installed (OpenCV and NumPy).

Download the 'haarcascade_frontalface_default.xml' Haar Cascade file. You can find it here.

Organize your image datasets into the 'datasets' directory. Each subdirectory should contain images of a specific person for face recognition.

Run the Python script in your preferred Python environment.

How It Works
The script creates a Fisher Face Recognizer model from the provided image datasets.
It then uses this model to detect and recognize faces in real-time through your webcam stream.
Detected faces are outlined with rectangles, and recognized faces display the identified name and confidence level.
Please ensure proper lighting conditions while using the face recognition feature.