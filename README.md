# Car Make, Type and Color Detection (CMTCD) example with YOLOv4 object detector

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Python example forked from [Spectrico's Github](https://github.com/spectrico). It combines Spectrico's Car Detection Projects with some minor changes made by me. It is a really simple implementation of AI Object Detection using YOLOv4 (OpenCV2 DNN and MNN backend from MobileNet) on Streamlit.

---
## Object Detection and Classification in images
The app is deployed using Streamlit. It takes an image as input, detects the cars using YOLOv4 object detector, crops the car images, makes them square while keeping the aspect ratio, resizes them to the input size of the classifier, and recognizes the color, make and type of each car.

#### Usage
Just fork this and deploy it using Streamlit.
