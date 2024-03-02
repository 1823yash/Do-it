Thermal Video Component Analysis

This Python project analyzes thermal video data to identify connected components with specific frequency characteristics. The main objective is to provide a tool for researchers and enthusiasts interested in thermal video analysis and connected component identification.

Features

Frequency Analysis: Utilizes Fast Fourier Transform (FFT) to calculate the dominant frequency in each frame of the thermal video.
Connected Component Identification: Applies connected component analysis based on the specified frequency range, identifying regions where pixels share similar thermal characteristics.
Google Drive Integration: Automatically downloads the thermal video from a provided Google Drive link.
Real-Time Visualization: Displays visualizations of connected components in real-time.

Requirements

Python 3.x
OpenCV
NumPy
SciPy
Matplotlib
gdown
