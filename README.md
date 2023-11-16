# Shape Reconstruction from 2D Images in Computer vision

## Introduction
Welcome to the Shape Reconstruction project! This project focuses on reconstructing the 3D shape of objects from 2D images using computer vision techniques. Two main approaches are explored: corner point detection and structure from motion (SfM).

## Datasets (Containing 2D Images)
- 6 folders containing images for the project (You can use any one for the project like castle 10,19,30,etc.)

## Libraries Used:
- Pandas
- Numpy
- Axes3d (for plotting in 3d)
- openCV
- Matplotlib
- tqdm (for python progress bars like loading symbol)

## Corner Point Detection and 3D Reconstruction
This approach involves:

1. **Corner Detection**: Utilizing Harris corner detection to identify key corner points in 2D images.
2. **Correspondence Matching**: Matching corner points across images using SIFT descriptors and RANSAC.
3. **Triangulation**: Reconstructing 3D points from the matched corner points.

## Structure from Motion (SfM)
The SfM approach includes:

1. **Feature Extraction**: Extracting feature points from images using SIFT descriptors.
2. **Feature Matching**: Matching feature points across images using a robust algorithm.
3. **Camera Pose Estimation**: Estimating the camera pose for each image.
4. **3D Reconstruction**: Reconstructing 3D points from feature points and camera poses.

## Results and Discussion
- Explore the project's results, compare the performance of each approach, and dive into the strengths and limitations of the methods.
- And inclued my term paper based on this project for that go to publications respiratory from this github profile then click publication pdf >> shape reconstruction

## Software Requirements
Ensure the following software is installed:
- **OpenCV**: For image processing and feature extraction.
- **MeshLab**: For visualizing and manipulating 3D models.


## Project Code
Organized into modules: 2 parts (creating 3d points from 2d images and cretaing a 3d scene/model from the 2d images)
1. **corner_detection**: Corner detection and matching code.  
2. **sfm**: SfM reconstruction code.

