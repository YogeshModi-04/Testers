# Introdution :
This Repository is concentrated to test your custom Object Detection Model of Model-Maker, Mediapipe-Model-Maker and TFOD.

## Some Basic Info:

### What is Model Maker ?
It is a Tensorflow-lite Framwork developed for edged devies that can run High level Models of Tensorflow in Tflite format.

The TensorFlow Lite Model Maker library simplifies the process of training a TensorFlow Lite model using custom dataset. It uses transfer learning to reduce the amount of training data required and shorten the training time.

* It have the following efficient-det models:
1. efficinetlite-0
2. efficinetlite-1
3. efficinetlite-2
4. efficinetlite-3
5. efficinetlite-4

For More Information :  [TF-Model Maker](https://www.tensorflow.org/lite/models/modify/model_maker)

### What is Mediapipe ?
MediaPipe is an open-source framework for building pipelines to perform computer vision inference over arbitrary sensory data such as video or audio. Using MediaPipe, such a perception pipeline can be built as a graph of modular components. MediaPipe is currently in alpha at v0.

* It have the following  models:
1. efficinetlite-0
2. SSD_MobileNet_V2
3. SSD_MobileNetMVG_V2

For More Information :  [Mediapipe Model Maker](https://developers.google.com/mediapipe)

![](https://storage.googleapis.com/prd-hatena-engineering-asset/20190304133208.jpg)

### About This Repository :
These Repo contains the testing Code to test-out custom object detection models will contain three jupter notebooks for each framworks testing.
 * Just replace the path of the Model.
 * I have trained my model using the script provided by google.
 * I have used to Gpt 3 to create scripts and debug myself to resolves the common errors. 

 ### Requirements:
 * tflite_model_maker
 * mediapipe_model_maker
 * cv2
 * Tensorflow-lite
 * Tensorflow
 * python 3.*("I am using 3.9.17")