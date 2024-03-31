# Damage Detection using Image Processing

This repository contains code for detecting damage in images of pipelines using image processing techniques. It provides scripts for preprocessing images, applying various filters and thresholds, and detecting and visualizing areas of damage.

## Overview

Damage detection in pipelines is crucial for ensuring structural integrity and preventing potential hazards. Traditional methods often involve manual inspection, which can be time-consuming and prone to errors. Automated damage detection using image processing techniques offers a faster and more accurate solution.

## Features

- **Image Preprocessing:** Apply Gaussian Blur and Unsharp Mask filters for noise reduction and enhancement of image details.
- **Thresholding:** Convert the enhanced image to binary mode using Adaptive Thresholding for clearer visualization of damage areas.
- **Morphological Operations:** Apply erosion to further refine the binary image and remove noise.
- **Contour Detection:** Find contours in the processed image to identify potential areas of damage.
- **Bounding Box Visualization:** Draw bounding boxes around detected damages on the original image for easy identification.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/damage-detection.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the scripts:

   - For detecting damage using image processing:
     ```bash
     python damage_detection.py
     ```

   - For generating heatmaps overlay:
     ```bash
     python heatmap_generation.py
     ```

4. Follow the instructions provided within the scripts for loading images and adjusting parameters as needed.

## Results

The repository provides visualizations of the original images with detected damages overlaid, along with processed images showing enhanced clarity and heatmap overlays highlighting potential damage areas.

## Contribution

Contributions are welcome! If you have any ideas for improvements, feel free to open an issue or submit a pull request.

