# Object-Detection-with-YOLO
## YOLO Object Detection with ResNet-50 Backbone

## Overview

This project demonstrates object detection using YOLO (You Only Look Once) architecture with a ResNet-50 backbone. The implementation includes testing on a subset of images from the COCO dataset, custom YOLO loss function, and real-time object detection using a camera feed. The model have been trained on pascal-voc-2012 dataset. The resarch paper's link for reference: https://arxiv.org/pdf/1506.02640v5.pdf.

### Features

- YOLO (You Only Look Once) is a real-time object detection system that processes images in one forward pass through a deep neural network.
- ResNet-50 is used as the backbone architecture for feature extraction.
- Custom YOLO loss function implemented for training.
- Testing on a subset of images from the COCO dataset (a cow, few people and a bird)(you can find the results in the repo above).
- Real-time object detection using a camera feed.

## Setbacks:
Due to lack of fast gpus, I was only able to run the model for 30 epochs instead of 135 epochs in which the learning rate scheduler would have made huge effect on the model's performance and better results would have been achieved.


