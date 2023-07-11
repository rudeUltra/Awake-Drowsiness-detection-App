# Awake-Drowsiness-detection-App
<h2>Drowsiness Detection app For Drivers
made by OpenCV python and dlib library</h2>

<h4>Prevents accidents by alarming the driver when he/she feels drowsy Made by OpenCV, Python and dlib Library. Simple Interface using HTML/CSS and JavaScript</h4>

![](https://github.com/rudeUltra/Personal-portfolio/blob/main/assets/img/drowsiness.gif)



<h2>Working:</h2>


![](https://github.com/rudeUltra/Awake-Drowsiness-detection-App/blob/main/Awake-Drowsiness-Detection/static/assets/Screenshot%202023-07-11%20182824.png)

Basically We first detect a face using dlib's frontal face detector. Once the face is detected , we try to detect the facial landmarks in the face using the dlib's landmark predictor from which we only extract the eye and mouth region to calculate aspect ratio and determine whether the person is blinking or yawning..

