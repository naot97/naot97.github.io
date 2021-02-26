## Introduction
Yolov4 is a framework to help everyone who uses a conventional GPU can train a detection object model easily.
The model can applied in the real-time and hashigh quality. The main goal of this work is the summary the knowleage I studied.

## Background

A detector is composed 2 parts:
* A **backbone** can be pre-trained. For those detectors running on GPU platform, their backbone could be VGG , ResNet , ResNeXt ,or DenseNet.
* A **head** is usually categorized into two kinds, i.e., one-stage object detector and two-stage object detector.
* In recent years, people often insert some layers between backbone and head. These layers are usually used to collect feature maps from different stages. We
can call it the **neck** of an object detector.
