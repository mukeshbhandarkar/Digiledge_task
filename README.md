# Digiledge_task
## Digiledge Task for Computer Vision

## Problem Statement:
create a face recognition program using TensorFlow.

## solution

I created face recognition program with the help of public dataset which includes 5 ** celebraties ** from kaggle
[click here](https://www.kaggle.com/dansbecker/5-celebrity-faces-dataset) and i added my face pic into dataset for identifying faces as per task full dataset [click here](https://drive.google.com/open?id=1X57BZGw6NgyMWsLHZbRArYJ0hdoiL3oU).

### This tutorial is divided into five parts; they are:

    Face Recognition
    FaceNet Model
    How to Load a FaceNet Model
    How to Detect Faces for Face Recognition
    How to Develop a Face Classification System.

as per task rule we use 'transfer learning' for training.
###There are a number of projects that provide tools to train FaceNet-based models and make use of pre-trained models.

Perhaps the most prominent is called OpenFace that provides FaceNet models built and trained using the PyTorch deep learning framework.

Download the model file and place it in your current working directory with the filename [‘facenet_keras.h5‘](https://https://drive.google.com/drive/folders/1pwQ3H4aJ8a6yyJHZkTwtjcL4wYWQb7bn)

And we are working with facial classification

Before we can perform face recognition, we need to detect faces.

Face detection is the process of automatically locating faces in a photograph and localizing them by drawing a bounding box around their extent.
we will also use the Multi-Task Cascaded Convolutional Neural Network, or MTCNN, for face detection, e.g. finding and extracting faces from photos.


### Loss function i used
'Triplet loss function'
The idea of comparative loss can be further extended from two examples to three, called triplet loss.
The loss function penalizes the model such that the distance between the matching examples is reduced and the distance between the non-matching examples is increased.
The triplets that are used to train the model are carefully chosen.
Triplets that are easy, result in a small loss, and are not effective at updating the model. Instead, hard triplets are sought that encourage changes to the model and the predicted face embeddings.

References:

FaceNet: A Unified Embedding for Face Recognition and Clustering, 2015.[here](https://arxiv.org/abs/1503.03832)

OpenFace Keras Project, GitHub.[here](https://github.com/iwantooxxoox/Keras-OpenFace)

NOte: I'm Using 
> google colab 
