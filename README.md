# Facial-Recognition-using-InceptionResnetV1
A pre-trained network to perform facial recognition on Bollywood celebrities

## Topic
In this notebook I will experiment with facial recognition using InceptionResnetV1 which is a hybrid architecture of the Inception network and ResNet network, which was pre-trained on the
the VGGface2 dataset (a huge dataset containing millions of faces classified into thousands of classes. The dataset I will be using contains faces of bollywood celebrities (I chose only 5
people for the sake of fast training). So first I will use the cascade classifier to detect and crop faces in the pictures and then the InceptionResnetV1 to classify these pictures into
classes representing the person they belong to. So let's get started !

## Obejctives
- Detect faces contained in images
- Apply facial recognition pre-trained network to recognize the person in the picture

## Summary
- Importing libraries
- The dataset
- Data transforms and loaders
- Data visualization
- Building the network
- Training the network
- Testing the network
- Inference
- Conclusion

## Libraries
- Numpy
- Torchvision
- CV2
- Glob
- FaceNet pytorch

## Data source
https://www.kaggle.com/datasets/hemantsoni042/celebrity-images-for-face-recognition?select=celebrities_images&fbclid=IwAR1Zu0URVfkPwqtcq2Or9IceRCQz_DTdlFs4HXoPKB0w_wbCrLterQe_DI4
