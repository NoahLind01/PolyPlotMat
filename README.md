#ProFileViewer - Polysome Profiling Data Viewer and Analysis Tool

## Overview
ProFileViewer is a MATLAB application for viewing and analyzing polysome profiling data. This tool provides an interactive interface for examining absorbance and fluorescence data from polysome profiles, with features for data comparison, area under the curve (AUC) measurement, and relative abundance calculations.

## Features

- **Main Panel**
  - Load CSV data files from a selected directory
  - Display absorbance/fluorescence data with customizable visualization parameters
  - Save data to a workspace for ongoing analysis

- **Comparison Panel**
  - Plot multiple traces simultaneously for direct comparison
  - Adjust individual plot colors and axes
  - Control left and right y-axes for absorbance and fluorescence data
  - Shift data along the x-axis for alignment

- **Analysis Panel**
  - Select regions of interest on polysome profiles
  - Calculate area under the curve for selected regions
  - Determine relative abundance percentages
  - Export analysis results as CSV files

## Requirements

- MATLAB (R2020b or later recommended)
- MATLAB App Designer

## Usage Instructions

### Main Panel
1. Click **Change Directory** to navigate to your data folder
2. Select a file from the dropdown menu to display
3. Choose the channel (Absorbance, Fluorescence, etc.) to visualize
4. Use **Load to Workspace** to save data for further analysis
5. Adjust Y-axis limits manually or enable auto-scaling

### Comparison Panel
1. Select multiple files from the workspace list (use Ctrl+click for multiple selection)
2. Choose the channel to display
3. Click **Plot Selected** to display the traces
4. Adjust individual trace colors using the color picker
5. Use the Y1/Y2 Min/Max fields to adjust axis limits

### Analysis Panel
1. Select a file from the workspace dropdown
2. Choose the appropriate channel
3. Click **Select Points** and then click on the plot to mark regions of interest
4. Click **Calculate AUC** to measure the area under the curve
5. View results in the table display
6. Use **Export CSV** to save analysis results

## Copyright and License
This application is not for modification, sale, or distribution without express permission from the author.

## Author
Proprietary software - all rights reserved

---

*Note: For technical support or to request permission for use beyond the standard license, please contact the author directly.*
