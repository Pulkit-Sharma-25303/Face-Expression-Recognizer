# Face-Expression-Recognizer using Deep Learning
This project implements real-time facial expression recognition using a Convolutional Neural Network (CNN) trained on the FER2013 dataset. The model can detect human faces in a video stream and classify the emotion expressed as one of seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. The final output is saved as a processed video file, showing detected faces and their corresponding emotions in real-time.
# Project Features
* Detects faces in video frames using Haar Cascade Classifier.
* Classifies the emotion using a CNN model trained on the FER2013 dataset.
* Outputs a video with detected faces and their associated emotions displayed in real-time.
* Capable of handling video input from a file in Google Colab.
* Displays the final output video within the Colab notebook.
# Dataset
The model is trained using the FER2013 dataset, which contains 35,887 grayscale images of faces, each labeled with one of seven emotions.
# Requirements
To run this project, you'll need the following libraries:
* TensorFlow/Keras (for deep learning)
* OpenCV (for face detection and video processing)
* NumPy
# Model
The model is a Convolutional Neural Network (CNN) trained on the FER2013 dataset. The network consists of convolutional, pooling, and fully connected layers. The final output is a softmax layer that classifies the emotion of the detected face into one of the following categories:

* Angry
* Disgust
* Fear
* Happy
* Sad
* Surprise
* Neutral
