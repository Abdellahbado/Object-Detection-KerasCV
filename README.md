# Object Detection with Keras

## Overview
This repository contains code for object detection using Keras. The code is adapted from Keras CV documentation, aimed at detecting objects in images. However, please note that the training process was not completed due to limitations in time and computational resources.

## Dataset
The dataset used for training this object detection model is available through the following website: [Self-Driving Car Object Detection Dataset](https://public.roboflow.com/object-detection/self-driving-car). After downloading the dataset, it needs to be extracted to the working directory.

## Code Description
The main script `object_detection.py` contains code for:

1. Data preprocessing: Moving images and annotations to appropriate directories and parsing annotations.
2. Dataset creation: Creating TensorFlow `Dataset` objects for training and validation.
3. Model setup: Defining the YOLOV8 object detection model architecture.
4. Training: Training the model using the prepared dataset.
5. Evaluation: Evaluating the trained model's performance using COCO metrics.
6. Visualization: Visualizing detection results on sample images from the dataset.

## Requirements
- TensorFlow
- Keras
- keras_cv
- xml.etree.ElementTree
- tqdm

## Usage
1. Clone the repository.
2. Download the dataset from the provided link and extract it to the working directory.
3. Run the `object_detection.py` script.

## Note
- Since the training process was not completed, the provided code can serve as a starting point for further experimentation and training on more powerful hardware.
- Feel free to modify the code according to your requirements and dataset.
