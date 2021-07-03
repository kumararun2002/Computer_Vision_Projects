# Computer_Vision_Projects
This repo contains the Computer vision projects done by me.

## Face and Face Mask Detection
Dataset link:- https://drive.google.com/drive/folders/1-AHWbzSQzBSjIaKuj54EgXNZqt1j7mse?usp=sharing

Developed a model to identify human faces from a given image and predict whether they are wearing face masks or not.
Used pre-trained weights of a Caffe Model and OpenCV to detect human faces in an image and trained a 5-layered Convolutional Neural Net using Pytorch Lightning to predict whether the person is wearing a face mask or not.
Trained model on COVID Face Mask detection Dataset (Kaggle).

## Detecting COVID-19 using Chest X-Ray
Dataset :- COVID-19 Radiography Database from Kaggle 

Predicted whether the Chest X-Ray is of a Covid patient or a viral fever patient or a normal person with 98.89 percent accuracy.
Used ResNet-18 pretrained model with Data Augmentation using batch gradient descent (batch size=6).
Deep Learning Framework used is Pytorch.
