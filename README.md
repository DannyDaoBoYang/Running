# Running
 MATLAB prediction whether the subject is running or walking given data from the accelerometer and gyroscope on their phone.
 
 This program uses MatLabs classification Learner feature.
 
 The modle is trainedModel.m
 
 The model is construct with Fine KKN modle based on features: accx, accy, accz, gyrox, gyroy, gyroz from the given data set.
 
 Due to computing issues, the model is trained with the first 3999 subjects and is tested against the first 7999 subjects.
 
 The model has a 98.1% accuracy against the given data.

The Data set is found on Kaggle
https://www.kaggle.com/vmalyi/run-or-walk
