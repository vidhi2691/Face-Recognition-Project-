# Face-Recognition-Project-
Face Recognition Project using Keras and Tensorflow

Steps Involved :
Step 1 - Face detection:
         
         Face detection in image using MTCNN(Multi-Tast Cascaded Convolutional Neural Network)
         Which detects faces and facial landmarks on images. It is the most acurate and  popular face detection tool.

Step 2 - Face Embeddings:
         
         Face Embeddings, i.e extracting the most important feature from face detected above, using FaceNet.
         FaceNet is a deep neural network used for extracting features from an image of a persons face. 
         Model which is used here is by Hiroski Taniai, which is a pre-trained keras model.
         
Step 3 - Face Classification:
         
         Face Classification, classifying the face based on extracted features using SVM(Support Vector Machine)classification.
         Softmax classifier can also be used, but here SVM is used as it gives better result then Softmax.
