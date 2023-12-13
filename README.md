# Object-Detection-YoloV3-Complete-Guide
This is a complete Guide of using Yolo_V3 for object detection examples

# Introduction
The objective of this project is to develop an object detection model using YOLO (You Only Look Once) to identify and classify various types of vegetables and fruits in images. 
The model will be trained on a dataset containing 100 images of 10 different types of vegetables and fruits. The trained model will then be evaluated on real Canadian Superstore flyers (can be found in the flyer section of their website, very few weeks new flyers are released by the store) to detect and classify the presence of vegetables or fruits. 
The model should be capable of detecting multiple instances of vegetables or fruits within a single flyer and provide a probability score for each detected class.

#  Dataset Description
The training dataset should consist of 100 images representing 10 different types of vegetables or fruits. 
Each image contains objects of one or more classes, along with labeled bounding boxes for each object. 
The test dataset will be comprised of real Canadian Superstore flyers, where the goal is to detect and classify vegetables or fruits depicted in the flyer images.

# Python Files
- Autoimage download google multiple object detection
This file is for Data Preparation and Preprocessing
Collect and curate a diverse dataset of images containing 10 types of vegetables or fruits. Ensure proper LabelImg of object classes and bounding boxes.
Preprocess the images and annotations for compatibility with YOLO object detection framework.

#Train and test YOLOV3
This file is for mplementing and configuring the YOLO object detection model using a suitable framework.
Train the model on the prepared training dataset using appropriate hyperparameters. Monitor the training progress and ensure convergence.
For testing I evaluated the model's performance in terms of precision, recall, and mean Average Precision (mAP).

