# Recognition of American Sign Language Alphabets

In this project I have build models based on dataset from Kaggle which contains images of hand gestures for alphabets of American sign language(ASL).
So in this dataset there are total 87,000 images which are 200x200 pixels. There are 29 classes, of which 26 are for the letters A-Z 
and 3 classes for SPACE, DELETE and NOTHING.

Link to dataset: https://www.kaggle.com/datasets/grassknoted/asl-alphabet

I have build different types of models with this data. I have used mediapipe library to get hand gesture from image and tried to use that data differently.
Like building model based on positions got by using functions from mediapipe, then converting them into angles with different methods and build model
based on them and finaly used convolutional neural network (CNN) and it performed better than all models with accuracy of 99%. But I have not used data 
augmentation techniques which can be easily achieved by tensorflow.keras.preprocessing.image.ImageDataGenerator function.
