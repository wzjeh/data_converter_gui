# data_converter_gui
This code is a PyQt5-based GUI tool that supports converting semicolon-separated text data into numpy arrays, LaTeX tables, and pandas DataFrame formats, and can be packaged into a Windows executable file.


# Data Conversion Tool

## Project Description
**Data Conversion Tool** is a graphical user interface application based on PyQt5, designed to help users convert semicolon-separated text data into multiple formats, including numpy arrays, LaTeX tables, and pandas DataFrames. Users can input data through the interface, select the conversion type, and copy the results. The tool supports packaging into a Windows executable file (`.exe`) for easy distribution and use.

**Creator**: 紫薯神 (Zishushen)  
**Created On**: 2024-09-26  
**Last Updated**: 2025-05-30

## Features
- **Convert to numpy Array**: Converts input data into `numpy.array` format.
- **Convert to LaTeX Table**: Generates LaTeX table code.
- **Convert to pandas DataFrame**: Converts semicolon-separated data into `pandas.DataFrame` format with default column names `column1`, `column2`, `column3`.
- **Copy Results**: Supports one-click copying of conversion results to the clipboard.

## Usage Instructions
1. **Install Dependencies**:
   Ensure Python (recommended version 3.8 or 3.9) is installed, then install the required libraries:
   ```bash
   pip install PyQt5 pandas numpy
