1) Project Overview
This project demonstrates a modular Python image processing system designed to showcase practical application of fundamental image processing techniques. The system processes input images through multiple stages, including color adjustment, filtering, noise reduction, edge detection, and feature extraction. The goal is to prepare images for further analysis or classification tasks by applying these key operations.


2) How to Run the Code
Requirements:
- Python 3.x
- OpenCV (OpenCV-python)
- NumPy

Usage:
Place your image file (.jpg, .png, or .tif) in the project directory or provide the full file path.
Run the script from the command line or inside a Jupyter/Colab notebook by providing the image path as an argument.


3) Description of Techniques Used
- Color Adjustment: Modifies image brightness and contrast using OpenCV's convertScaleAbs method to enhance image appearance.

- Gaussian Blur: Applies Gaussian filtering to reduce image noise and smooth details.

- Non-local Means Denoising: Performs advanced noise reduction that preserves edges and important details.

- Canny Edge Detection: Detects edges by finding intensity gradients, extracting object boundaries.

- Feature Extraction: Uses ORB (Oriented FAST and Rotated BRIEF) algorithm to identify keypoints and compute descriptors for potential classification tasks.


4) Known Limitations and Notes
- Parameter values (brightness, contrast, blur size, denoising strength) are hardcoded but can be modified within the script.

- ORB feature extraction is basic and could be replaced with more advanced techniques for classification-ready features.

- Large images may cause slower processing; resizing is recommended for efficiency.

- The project is a command-line based tool without GUI.

- Exception handling ensures fault tolerance, but user input must be valid file paths.
