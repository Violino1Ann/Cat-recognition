# Cat recognition
Developent of Android application that estimates probability of presence of a domestic cat in the picture

Structure:
1. Dataset : https://yadi.sk/d/_mPGtFAyGJH44A
2. train model : code of Keras model training based on kernel https://www.kaggle.com/uysimty/keras-cnn-dog-or-cat-classification
    acc: 0.9694
val_acc: 0.9172
3. Android application project (Kotlin) : https://yadi.sk/d/maOCjg0MQwX-eA 
(based on Udacity Course "Introduction to TensorFlow Lite" resource https://classroom.udacity.com/courses/ud190/lessons/36117ba3-7ddb-4eb9-8705-ff5504a1d036/concepts/8cfdd16f-ea66-4994-b984-aa8ce316a9f2)

4. Other files related to the project:
- ImageClassifierActivity.kt : "cat" probability estimation of chosen image from application's gallery
- Classifier.kt : image scaling + prediction
- TF-Lite converted model : https://yadi.sk/d/ADKNEMXnef0o5A
- Android application for model infering: results representation (test set images img1-img6.jpg recognition)
