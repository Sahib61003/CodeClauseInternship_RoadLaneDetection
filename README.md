# Road Lane Detection Project as AI Intern at CODECLAUSE 

## Overview
This project is a part of my internship at CODECLAUSE. The goal of this project is to detect road lanes in a video stream.This project is based on the detection of road lanes. It is the base step of creating a self driving car project. In this I have collected the images data from kaggle. It involves processing images of roads to identify and highlight lane markings. The pipeline includes steps like grayscale conversion, edge detection, region of interest masking, and Hough line transformation.

## Libraries Used
The project is implemented using the following libraries:

* For Image Processing 
- OpenCV: Used for image processing tasks such as edge detection, Hough line transformation, and image blending.
- NumPy: Utilized for numerical operations and array manipulation, essential for image data handling.
- Matplotlib: Employed for data visualization, allowing the display of images, plots, and graphical results.

* For File Operations
- os: Used for file operations and directory listing to process multiple images.

## Pipeline
The pipeline is implemented in the following steps:
1) Read all files from a given folder into an array.
2) Convert the image to grayscale and apply gaussian blur.
3) Apply canny edge detection to the image.
4) Define a region of interest and mask the image.
5) Apply Hough line transformation to the image.(primarly to 2nd image in my project)
6) Apply weighted image function to blend the image with the original image.
7) Display the final output on screen or save it to disk depending upon user input.



