# Car Make, Type and Color Detection (CMTCD) example with YOLOv4 object detector

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Python example forked from [Spectrico's Github](https://github.com/spectrico). It combines Spectrico's Car Detection Projects with some minor changes made by me. It is a really simple implementation of AI Object Detection using YOLOv4 (OpenCV2 DNN and MNN backend from MobileNet) on Streamlit.

---
## Object Detection and Classification in images
The app is deployed using Streamlit. It takes an image as input, detects the cars using YOLOv4 object detector, crops the car images, makes them square while keeping the aspect ratio, resizes them to the input size of the classifier, and recognizes the color, make and type of each car.

#### Usage
Just fork this and deploy it on Streamlit.

## Credits
This app is based on Spectrico's app on Github with some minor changes so i could deploy it using Streamlit.
Spectrico's created it based on the tutorial by Adrian Rosebrock: [YOLO object detection with OpenCV](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)
The YOLOv4 object detector is from: [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
The make and type classifier is based on MobileNet neural network architecture: [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861)
