EDGE_DETECTION
(ALONG WITH THE NOTES FILE WHICH CONSIST OF DEFINATION AND SOME EXPLORATION OF THE TOPIC WITH THE HELP OF OPEN AI)

This repository contains implementations and demonstrations of various classical edge detection techniques using OpenCV in Python. The techniques explored include Sobel, Laplacian, and Canny edge detectors on grayscale images.

Project Overview
Edge detection is a fundamental task in computer vision and image processing. It helps to identify boundaries and important features in images by detecting sharp changes in intensity. This repository compares and visualizes the effects of three popular edge detection methods:

Sobel Edge Detector: Computes image gradients in the x and y directions and combines them to highlight edges.

Laplacian Edge Detector: Uses the second derivative to detect edges regardless of their orientation.

Canny Edge Detector: A multi-stage algorithm that includes noise reduction, gradient calculation, non-maximum suppression, and hysteresis thresholding to produce clean edges.

Repository Contents
Edge_detection.ipynb: Jupyter Notebook demonstrating the loading of a grayscale image, applying Sobel, Laplacian, and Canny edge detection, and visualizing results using matplotlib.

Technologies and Libraries Used
Python 3.x

OpenCV (cv2)

Matplotlib

NumPy

How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Aryan-1912/EDGE_DETECTION.git
Navigate to the project directory:

bash
Copy
Edit
cd EDGE_DETECTION
Install required libraries if not already installed:

bash
Copy
Edit
pip install opencv-python matplotlib numpy
Open and run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Edge_detection.ipynb
Follow the notebook steps to see the edge detection results.

Key Functions Demonstrated
cv2.Sobel(): Computes gradients along x and y directions.

cv2.Laplacian(): Calculates the Laplacian (second derivative) of the image.

cv2.Canny(): Performs Canny edge detection with specified thresholding.

Visual Results
The notebook displays:

Original grayscale image

Sobel edge magnitude image

Laplacian edge image (raw and absolute scaled)

Canny edge detected image

Future Work
Extend to color images and multi-channel edge detection.

Experiment with different kernel sizes and threshold values.

Implement other edge detection methods like Prewitt or Roberts.

Author
Aryan Prajapati
