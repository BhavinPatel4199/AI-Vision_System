# AI-Vision_System

- This repository contains projects focused on computer vision techniques using Python and OpenCV.
- The projects are designed to help users understand and implement various image processing algorithms and techniques, ranging from basic operations to advanced computer vision algorithms.

## Overview

This repository showcases the implementation of various computer vision techniques using Python and OpenCV. It is divided into two main projects:
1. **OpenCV Operations - Python Exercises**: A collection of exercises aimed at familiarizing users with basic OpenCV operations.
2. **Vision System Algorithms Implementation**: An implementation of advanced computer vision algorithms for practical applications such as feature detection, image segmentation, and object recognition.

## Projects

### 1. OpenCV Operations - Python Exercises

This project consists of a series of exercises that guide you through basic image processing techniques using OpenCV. The exercises cover operations such as image resizing, color space conversions, drawing shapes, applying filters, and performing edge detection.

#### Contents
- **Reading and displaying images**: Understanding image properties such as shape and size.
- **Image creation and manipulation**: Using NumPy arrays to create and modify images.
- **Color space conversions**: Working with RGB and HSV color spaces.
- **Image scaling**: Applying different interpolation methods for image resizing.
- **Drawing shapes and regions of interest**: Drawing, cropping, and rotating shapes in images.
- **Thresholding and edge detection**: Applying filters and edge detection techniques.
- **Interactive image manipulation**: Creating scripts for drawing shapes interactively on images.

### 2. Vision System Algorithms Implementation

This project demonstrates the implementation of advanced computer vision algorithms using OpenCV. Each algorithm addresses different problems in computer vision, such as feature detection, image segmentation, and object recognition.

#### Implemented Algorithms
- **Harris Corner Detection**: Identifies significant changes in image intensity, useful for feature matching and object recognition.
- **Image Pyramids**: Represents images at multiple scales, useful for image blending and multi-scale analysis.
- **Watershed Algorithm**: Segments images into distinct regions based on pixel intensity levels.
- **SIFT (Scale-Invariant Feature Transform)**: Detects and describes local features in images, robust to scale, rotation, and illumination changes.
- **YOLO Object Detection**: A real-time object detection system that identifies objects by predicting bounding boxes and class probabilities.

## Dependencies

To run the projects in this repository, you will need the following Python libraries:

- OpenCV
- NumPy
- Matplotlib
- PIL (for OpenCV Operations - Python Exercises)

- **You can install these dependencies using pip:**
  ```bash
  pip install opencv-python-headless numpy matplotlib pillow


## How to Run

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/artificial-intelligence-vision-system.git
    cd artificial-intelligence-vision-system
    ```

2. **Navigate to the Project Directory:**
    - For OpenCV Operations:
      ```bash
      cd opencv-operations-python-exercises
      ```
    - For Vision System Algorithms:
      ```bash
      cd vision-system-algorithms-implementation
      ```

3. **Run the Scripts:**
    - Follow the instructions in each project’s `README.md` file for running individual scripts.
