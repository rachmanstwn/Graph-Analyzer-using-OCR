# Graph Color Detector

This project contains a color detection tool for graph analysis using OpenCV. It is designed to assist in identifying and extracting color-coded information from graphical plots such as line charts or bar graphs.

## Project Overview

The tool is composed of two main Python scripts:

- `color_analyzer.py`: A utility for identifying and classifying distinct colors present in an image.
- `graph_analyzer.py`: A script that processes graphs and matches the identified colors to specific data lines or bars for further analysis.

This is particularly useful for automated analysis of plotted data where each data series is represented by a different color.

## Dependencies

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy (`numpy`)
- (Optional) Matplotlib (for visualization)

You can install the required packages using pip:

```bash
pip install opencv-python numpy
