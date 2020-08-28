# Facial Expression Recognition DCNN
This is the first DL project that I'm publishing. It is a Deep Convolutional Neural Network that I trained to recognize facial expressions using TensorFlow and [this](https://www.kaggle.com/sulthankhan/facial-expression-recognition) dataset. The DCNN is implemented using a python OpenCV script that detects faces using a HaarCascade and then feeds the faces into the model.
## Implementation
This file contains the script that uses the trained model to detect the expressions.
## Training
This is the notebook using which I trained the model on the proccessed data. The most successful model is included in this repository.
## Proccessing
Here is the script that was used to take the data and bring it into a format which can be used for training the model. Notice that the original dataset has seven categories: angry, fear, happy, neutral, sad, surprise and disgust. I decided to remove disgust for having way less samples that the other categories.
