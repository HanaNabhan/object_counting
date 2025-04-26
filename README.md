# Object Counting using Computer Vision
This project demonstrates object counting on images using classical computer vision techniques with the Pascal VOC 2012 dataset.

We preprocess images by applying grayscale conversion, histogram equalization, Gaussian blurring, Canny edge detection, dilation, and finally contour detection to count objects.
Steps
Dataset Preparation:
Downloaded Pascal VOC 2012 and selected 1000 images + annotations.

## Preprocessing:

Grayscale conversion

Histogram Equalization

Gaussian Blur

## Edge Detection:

Canny edge detection

Dilation to close gaps

## Contour Detection:

Find contours

Filter by area

Count objects

## Requirements
Python 3

OpenCV

Matplotlib

Numpy
