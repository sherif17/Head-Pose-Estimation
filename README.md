# Head-Pose-Estimation

In this project I've worked on AFLW2000-3D dataset which is a dataset of 2000 images that have been annotated with image-level 68-point 3D facial landmarks, with various head poses for humans and animations. By using mediapipe to extract faces landmarks which are 468 points in 3D, but we used x-axis & y-axis

## Work-flow

* Preparing data for model training ( we used MediaPipe and CV2 libraries for extracting points and for face detection from pictures).
* Spliting the data to training, validation and testing.
* Using regression model.
* Detecting a random pic to validate the model from dataset.

## Demo video:
https://user-images.githubusercontent.com/43541909/219964912-079c3993-9178-461f-9a0b-281e4a49a8e2.mp4

## Libraries used:

* MediaPipe
* Numpy
* OpenCV
* Matplotlib
* Pandas
* Scikit-Learn
