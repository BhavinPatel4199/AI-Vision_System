# Vision System Algorithms Implementation

This repository contains the implementation of several computer vision algorithms using OpenCV. The implementations are part of an assignment focused on applying different techniques in image processing and computer vision. Each algorithm is implemented in Python, utilizing the OpenCV library for image manipulation and analysis.

## Dataset : 
1. Images used in this project are uplaoded in repository feel free to use your own images.
2. For yolo object detection i have used the dataset named "val2017" : link to download the data set (http://images.cocodataset.org/zips/val2017.zip)

## Overview

This project showcases the implementation of fundamental computer vision algorithms to address various problems such as feature detection, image segmentation, and object recognition. The goal is to demonstrate practical applications of these algorithms in Python using the OpenCV library. This repository is intended for educational purposes, providing clear, executable code that can serve as a reference or learning tool.

## Implemented Algorithms

### Harris Corner Detection
- Harris Corner Detection is used to identify points in an image where there is a significant change in intensity in multiple directions. This technique is useful for feature matching and object recognition in computer vision.

### Image Pyramids
- Image Pyramids are a representation of the same image at different scales. This concept is useful for tasks such as image blending, super-resolution, and multi-scale analysis, providing a way to process images at multiple resolutions.

### Watershed Algorithm
- The Watershed algorithm is utilized for image segmentation, dividing an image into distinct regions based on pixel intensity levels. This method is effective for separating different regions in an image, which can be used for further analysis or processing.

### SIFT (Scale-Invariant Feature Transform)
- SIFT is a feature detection algorithm that identifies and describes local features in images. It is robust to changes in scale, rotation, and illumination, making it suitable for various applications in feature matching and object recognition.

### YOLO Object Detection
- YOLO (You Only Look Once) is a real-time object detection system that identifies objects in images by predicting bounding boxes and class probabilities. This state-of-the-art technique allows for accurate and fast object detection.


## Dependencies
To run the code in this repository, you will need the following Python libraries:
OpenCV
NumPy
Matplotlib



## Required Files

  For YOLO Object Detection to work, you need the following files:
  1. coco.names: This file contains the names of the classes that YOLO can detect. It is used to label the detected objects.
  - Location: Typically provided with YOLO weights or can be downloaded from the YOLO website.
  - Usage: Place it in the same directory as your YOLO scripts.
  2. yolo3.cfg: This configuration file defines the YOLO model architecture and hyperparameters.
  - Location: Usually obtained from the YOLO website or trained models.
  - Usage: Specify the path to this file when loading the YOLO model in your script.
  3. yolo3.weights: This file contains the trained weights for the YOLO model. It is essential for the model to make predictions.
  - Location: Downloadable from the YOLO website.
  - Usage: Ensure this file is accessible to your script and specify the correct path when loading the model.

#### All this files are present in the repository.

## Results

- Each script generates visual output demonstrating the algorithms functionality. The results include:

  - Corner detection highlights using Harris Corner Detection.
  - Multi-resolution representations of images using Image Pyramids.
  - Segmented regions based on intensity levels using the Watershed Algorithm.
  - Keypoint detection and feature description using SIFT.
  - Real-time object detection with bounding boxes using YOLO.

## Contributing

  - Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please follow these steps:

