# Image-Stitching-And-Camera-Matrix

This project is about stitching two images together using homography and camera matrix calculations. The project is implemented in Python and uses libraries such as OpenCV, NumPy, and Matplotlib.

## Project Overview

The project can be divided into the following steps:

1. **Image Preprocessing**: The images are read using OpenCV's `imread` function. They are then converted to grayscale and Gaussian blur is applied for noise reduction. The preprocessed images are saved for further use.

2. **Feature Extraction**: Points of interest are extracted from both images. These points are used to calculate the homography matrix.

3. **Homography Matrix Calculation**: A homography matrix is calculated using the points of interest from both images. This matrix represents the transformation from one image to the other.

4. **Image Warping**: The second image is warped using the calculated homography matrix. This warping aligns the features of the second image with the first.

5. **Image Stitching**: The warped second image and the first image are stitched together to create a panorama.

6. **Camera Matrix Calculation**: The camera matrix of the phone used to capture the images is calculated. This involves marking points on the image, establishing their world coordinates, and computing the camera matrix.

## Code Structure

The code is structured in a Jupyter notebook with cells corresponding to each step of the process. Each cell contains comments explaining the purpose of the code.

## Dependencies

- Python 3
- OpenCV
- NumPy
- Matplotlib

## Usage

To run the project, open the `Image-Stitching.ipynb` notebook in a Jupyter environment. Make sure to install all the dependencies listed above.

