# Ather_Teammate2_3D_Vision_Road_Curvature.ipynb
# Ather Two-Wheeler Perception System

## Project Overview
A forward-facing camera-based perception system designed to improve two-wheeler road safety through computer vision.

## Teammate 2 – 3D Vision and Road Curvature Estimation

### Objective 3: Stereo-Based 3D Vision
- Stereo disparity estimation using StereoSGBM
- Metric depth estimation
- 3D point-cloud reconstruction
- Ground-plane estimation using RANSAC
- Pothole and speed-breaker height estimation

### Objective 4: Road Curvature Estimation
- Road boundary extraction
- Polynomial curve fitting
- Curvature and radius estimation
- Straight, left-curve and right-curve classification

## Technologies
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Current Progress
- Core processing functions implemented.
- Synthetic ground-plane and hazard-height tests completed.
- Road-image processing and image-space curvature experiments performed.
- Real-world metric validation is pending camera calibration and verified road measurements.

## Running the Notebook
Open the `.ipynb` notebook in Google Colab and execute the cells in order.

## Limitations
Current road-curvature results are image-space estimates. Real-world measurements require camera calibration and ground-plane mapping. Stereo depth requires calibrated and rectified stereo image pairs.
