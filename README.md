This project demonstrates how face detection (and basic mask detection) can be performed using Python and OpenCV.

🔹 What is the main goal?

The main aim of this project is to detect human faces in images or video using a classical computer vision technique called Haar Cascade Classifier.
An additional notebook explores face mask detection, which checks whether a detected face is wearing a mask or not.

🔹 How does it work?

1️⃣ Haar Cascade Classifier

The file haarcascade_frontalface_default.xml is a pre-trained model provided by OpenCV.

It is trained to recognize frontal human faces by detecting facial patterns like eyes, nose, and face structure.

2️⃣ OpenCV

OpenCV is used to:

Read images or video

Convert images to grayscale (Haar cascades work better on grayscale)

Detect faces using the cascade classifier

Draw rectangles around detected faces

3️⃣ Jupyter Notebooks

detection.ipynb

Loads an image or webcam feed

Applies the Haar Cascade model

Detects faces and displays bounding boxes around them

mask_detection.ipynb

Builds on face detection

Attempts to classify detected faces as mask or no mask

Useful for real-world applications like public safety monitoring

🔹 Technologies Used

Python

OpenCV

Jupyter Notebook

Haar Cascade XML model

🔹 Why this project is useful?

Beginner-friendly introduction to computer vision

Helps understand how real-time face detection works

Can be extended to:

Attendance systems

Security systems

Mask-detection applications

Face recognition (advanced)
