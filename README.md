## ProFileViewer - Polysome Profiling Data Viewer and Analysis Tool

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

ProFileViewer User Guide
Overview

ProFileViewer is a MATLAB application designed for analyzing polysome profiling data. It allows visualization, comparison, and quantification of both absorbance and fluorescence signals across polysome fractions.
Getting Started

    Launch the application in MATLAB by running ProFileViewer_V5
    Use the Change Directory button to navigate to your data folder
    Select CSV files containing your polysome profile data

## Main Features
Data Visualization (Main Panel)

    Browse and select CSV files from the dropdown menu
    Choose channels (Absorbance, FluorA, FluorB) to display
    Adjust Y-axis limits manually or enable auto-scaling
    Save files to workspace for further analysis

Data Comparison (Comparison Graphing)

    Plot multiple profiles simultaneously for direct comparison
    Select different channels to compare across samples
    Customize colors and adjust axes independently
    Shift traces horizontally for alignment

Quantitative Analysis (Trace Analysis)

    Select Data Source:
        Choose a file from the workspace dropdown
        Select the channel to analyze (absorbance, fluorescence)

    Mark Regions:
        Click the Select Points button
        Click on the plot to mark boundaries of regions (e.g., monosome, disome, etc.)

    Calculate Area Under Curve:
        Click the Calculate AUC button
        Results display both absorbance and available fluorescence data
        The All Fluoro switch toggles baseline correction for fluorescence

    Interpret Results:
        The table shows segments, AUC values, and relative percentages for all channels
        Results are color-coded for different data types

    Export Data:
        Click Export CSV to save your analysis
        The exported file includes metadata and results for all channels

Tips for Multi-Channel Analysis

    Absorbance Data (260nm): Measures RNA content, revealing polysome distribution
    Fluorescence Channels: Reveal distribution of specific fluorescently-tagged proteins
    Baseline Correction: The "All Fluoro" switch adjusts baseline for fluorescence channels
    Segment Selection: Carefully mark boundaries between ribosomal fractions for consistent analysis

Suggested Workflow

    Load all files to workspace using Load All to Workspace
    Use the comparison panel to get an overview of your profiles
    Switch to the analysis panel for quantitative measurements
    Select consistent fraction boundaries across samples
    Calculate AUC for each sample with the same boundary selections
    Export data for statistical analysis in your preferred software

Troubleshooting

    If channels aren't appearing in the dropdown, ensure your CSV file has standard column names (AbsA, SampleFluorA, etc.)
    For cleaner fluorescence analysis, enable the "All Fluoro" switch when analyzing noisy fluorescence data
    If the application fails to calculate AUC, try selecting fewer points to define simpler regions


## Copyright and License
This application is not for modification, sale, or distribution without express permission from the author.
All rights reserved
