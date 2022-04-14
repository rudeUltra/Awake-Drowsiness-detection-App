# Awake-Drowsiness-detection-App
Drowsiness Detection app For Drivers
made by OpenCV python and dlib library

Working:

Basically We first detect a face using dlib's frontal face detector. Once the face is detected , we try to detect the facial landmarks in the face using the dlib's landmark predictor from which we only extract the eye and mouth region to calculate aspect ratio and determine whether the person is blinking or yawning..

![](https://github.com/rudeUltra/Awake-Drowsiness-detection-App/blob/main/Awake-Drowsiness-Detection/static/assets/frame_yawn1.jpg)

