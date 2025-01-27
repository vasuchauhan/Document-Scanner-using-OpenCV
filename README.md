# Document Scanner with OpenCV

This project implements a document scanning application using OpenCV, NumPy, and Matplotlib. The application takes an image of a document, processes it to detect the document's edges, and applies a perspective transformation to create a scanned effect. The output is a clean, binarized version of the document.

## Features

- **Image Preprocessing**: Resizes and blurs the input image to enhance edge detection.
- **Contour Detection**: Identifies the contours of the document in the image.
- **Perspective Transformation**: Warps the detected document area to produce a straightened scan.
- **Adaptive Thresholding**: Converts the warped image to a binary format for better readability.

## Requirements

To run this project, you need to have Python installed along with the following libraries:

- OpenCV
- NumPy
- Matplotlib

### I have included the further explaination regarding the working of this code within the Jupyter notebook. 

