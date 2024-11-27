# Video-Based Heart Rate Estimation

## Introduction

The analysis of videos to extract physiological information, such as heart rate, has gained popularity in recent years. This project aims to develop a method for analyzing videos using image and signal processing techniques to detect light intensity variations associated with heartbeats.

The main approach involves extracting color components from a Region of Interest (ROI) in each video frame and analyzing their variations over time. By applying filtering techniques and peak detection, we can estimate the heart rate of the person in the video. Additionally, frequency analysis provides insights into the signal's characteristics in terms of frequency components.

The project is structured into multiple steps, from selecting the ROI in the video to analyzing filtered signals and detecting peaks. Each section is designed to address a specific aspect of data processing and analysis using Python libraries like OpenCV, NumPy, SciPy, and Matplotlib.

The final objective is to deliver a robust method for estimating heart rate from videos, addressing challenges such as lighting variations, motion, and other artifacts that can affect the quality of extracted signals. This method can be applied to various videos, including those captured in clinical or home environments, for non-invasive health monitoring.

## Table of Contents

### I. Load and Select a Region in the Video
   - Video retrieval
   - ROI selection
   - Neutral region selection
   - Defining the zone size

### II. RGB Component Intensity Analysis in a Region
   - Extracting video frames
   - Calculating average RGB component intensities
   - Storing data and plotting graphs

### III. Filtered RGB Intensity Analysis and Peak Detection
   - Data filtering
   - Peak detection
   - Plotting filtered curves
   - Peak count and average heart rate (BPM)

### IV. Frequency Analysis of Filtered Signals
   - Fourier Transform computation
   - Frequency mapping
   - Plotting the frequency spectrum

### V. YCrCb Component Intensity Analysis
   - Color space conversion
   - Extraction and average calculations
   - Data storage and graph plotting

### VI. Filtering YCrCb Signals and Peak Detection
   - Data filtering
   - Peak detection
   - Plotting filtered curves
   - Peak count and average heart rate (BPM)

### VII. Frequency Analysis of Filtered YCrCb Signals
   - Fourier Transform computation
   - Frequency mapping
   - Plotting the frequency spectrum

### VIII. Neutral Zone Testing

### IX. Test on the Video with the American Subject

### X. Test on the Video with the Girl in Green

## Libraries Used

The project leverages the following Python libraries:

- **OpenCV**: For image and video manipulation.
- **Matplotlib**: For data visualization and plotting.
- **NumPy**: For numerical computations and multidimensional array manipulation.
- **SciPy**: For designing and applying numerical filters, as well as peak detection.

---

This project showcases a robust approach for heart rate estimation from videos using advanced processing and analysis techniques. It provides a framework that can be expanded for various real-world applications.
