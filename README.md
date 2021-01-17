# Car Make, Type and Color Detection (CMTCD) example with YOLOv4 object detector

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Python example forked from [Spectrico's Github](https://github.com/spectrico). It combines Spectrico's Car Detection Projects with some minor changes made by me. It is a really simple implementation of AI Object Detection using YOLOv4 (OpenCV2 DNN and MNN backend from MobileNet) on Streamlit.

---
## Object Detection and Classification in images
The app is deployed using Streamlit. It takes an image as input, detects the cars using YOLOv4 object detector, crops the car images, makes them square while keeping the aspect ratio, resizes them to the input size of the classifier, and recognizes the color, make and type of each car.

#### Usage
Just fork this and deploy it using Streamlit.


## Credits
The examples are based on the tutorial by Adrian Rosebrock: [YOLO object detection with OpenCV](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)

The YOLOv4 object detector is from: [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
```
@article{bochkovskiy2020yolov4,
  title={YOLOv4: Optimal Speed and Accuracy of Object Detection},
  author={Bochkovskiy, Alexey and Wang, Chien-Yao and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2004.10934},
  year={2020}
}
```
The car color and make classifier is based on MobileNetV3 mobile architecture: [Searching for MobileNetV3](https://arxiv.org/abs/1905.02244)
```
@inproceedings{howard2019searching,
  title={Searching for mobilenetv3},
  author={Howard, Andrew and Sandler, Mark and Chu, Grace and Chen, Liang-Chieh and Chen, Bo and Tan, Mingxing and Wang, Weijun and Zhu, Yukun and Pang, Ruoming and Vasudevan, Vijay and others},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={1314--1324},
  year={2019}
}
```
The car type classifier is based on MobileNet neural network architecture: [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861)
