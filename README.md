# Haris-corner-detection-algorithm
# Harris Corner Detection in Images
This repository contains a Python implementation for applying Harris Corner Detection to images, detecting corners, and highlighting them with a visual effect. The     project uses OpenCV for image processing and is intended to be run in a Python environment, such as Google Colab.
      

# Features
_Corner Detection:_ Detects corners in images using the Harris Corner Detection method.

_Corner Highlighting:_ Highlights the detected corners by marking them in red on the original image.

_Edge Detection Preprocessing:_ Applies Gaussian blur to reduce noise and enhance corner detection accuracy.

_Corner Counting:_ Counts the number of corners detected in each image.

_Visualization:_ Displays the images with the highlighted corners in Google Colab using matplotlib.

_Flexible Image Input:_ Works with a list of images by providing file paths.

# Usage
1 Clone the repository or copy the code.

2 Provide the paths to your images by replacing the image_paths list:

image_paths = 
    '/path/to/image1.jpg',  # Replace with your image file path
    '/path/to/image2.jpg',  # Replace with your image file path
    '/path/to/image3.jpg'   # Replace with your image file path

3 Run the code in your Python environment (e.g., Google Colab).
4 The script will output:
5 Displayed images with highlighted corners.
6 Printed number of corners detected in each image.
# Requirements
Python 3.x
OpenCV
NumPy
Matplotlib
Google Colab (optional, but preferred for displaying images)
