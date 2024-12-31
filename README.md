# Image to Cartoon Conversion

## Overview
This project converts real-world images into cartoon-style visuals using Python. The notebook utilizes advanced image processing techniques and libraries such as OpenCV, NumPy, and Matplotlib to implement the cartoonization process.

## Features
- Converts input images into cartoon-style visuals.
- Includes functions for preprocessing, edge detection, and image smoothing.
- Provides visual outputs for each step in the cartoonization pipeline.

## Requirements
Ensure you have the following libraries installed:
- IPython
- collections
- cv2 (OpenCV)
- matplotlib
- numpy
- scipy

Install missing libraries using pip:
```bash
pip install opencv-python numpy matplotlib scipy
```

## Functions
1. `K_histogram`: Performs histogram-related calculations, likely used for color quantization or clustering.
2. `cartoon`: Main function to apply cartoon effects, including edge detection and color smoothing.
3. `update_c`: Handles intermediate updates or calculations during processing.

## Algorithm
1. Edge Detection: Identifying prominent edges in the image using techniques such as Canny edge detection.
2. Color Quantization: Reducing the number of colors to create a cartoon-like appearance.
3. Smoothing: Applying bilateral filtering or similar techniques to smoothen color transitions.

## How to Run
1. Open the Jupyter notebook (`Image_to_Cartoon.ipynb`).
2. Change the image path to your image.
3. Execute each cell.
4. The final output will display the cartoonized image.

## Notes
- Ensure that OpenCV is properly installed as it handles most of the image processing tasks.
- For Google Colab users, additional steps for file uploads or downloads may be necessary.

## License
This project is licensed under the MIT License. Feel free to modify and distribute it as needed.
