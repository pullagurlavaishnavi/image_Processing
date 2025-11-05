#  Image Processing Algorithms 

##  Overview
This project demonstrates a series of **Digital Image Processing** techniques implemented using **Python**, **OpenCV**, **NumPy**, and **Matplotlib**.  
It was developed in **Google Colab** as part of an academic image processing assignment.

---

## ⚙️ Features Implemented

### 1. **Color Space Conversion**
- Manual conversion from **BGR → RGB** and vice versa (without using built-in functions).

### 2. **Histogram Equalization**
- Performed from scratch using **probability** and **cumulative distribution function (CDF)** to enhance image contrast.

### 3. **Frequency Domain Filtering**
- Implemented various filters using **custom DFT and IDFT**:
  - Ideal Low-Pass / High-Pass Filter  
  - Butterworth Low-Pass / High-Pass Filter  
  - Gaussian Low-Pass / High-Pass Filter  

### 4. **Hough Transform**
- Detects **electric lines** from an image using a manually coded Hough Transform algorithm.

### 5. **Noise Removal using Gaussian Filter**
- Adds and removes noise such as **salt & pepper** using Gaussian smoothing kernels.

### 6. **Image Restoration Techniques**
- Adds multiple noise types:
  - Impulsive Noise
  - Gaussian Noise
  - Gamma Noise
  - Exponential Noise
  - Uniform Noise
- Applies restoration filters:
  - Median Filter
  - Mean (Averaging) Filter
  - Gaussian Filter
  - Bilateral Filter
  - Non-local Means Denoising

### 7. **Spatial Filtering**
- Implements basic and advanced filters manually:
  - Mean Filter
  - Median Filter
  - Min & Max Filters
  - Geometric Mean Filter
  - Harmonic Mean Filter

### 8. **Edge Detection**
- Performs edge detection using:
  - Sobel Operator (manual)
  - Prewitt Operator (manual)
  - Canny Edge Detector (OpenCV)

---

##  Requirements

Install the following Python packages before running the notebook:

```bash
pip install opencv-python numpy matplotlib pillow

