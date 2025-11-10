
# Image Sharpness Map Generator

## Overview
This project computes a **Laplacian-based sharpness map** to measure local focus levels across an image.  
It visualizes sharper and blurrier regions using a **heatmap**, allowing users to quickly identify in-focus and out-of-focus areas.  Note- Sample image can be used for test.

### The the project uses:
- **Laplacian Operator** → Detects high-frequency regions (edges and textures).  
- **Variance of the Laplacian** → Estimates overall image sharpness numerically.  
- **Jet Colormap Visualization** → Represents sharpness intensity as a heatmap.

---

## ⚙️ Requirements

You can run this code in **Google Colab** or **Jupyter Notebook**.

### Required Python Packages
- `opencv-python`  
- `numpy`  
- `matplotlib`

Install them using the following command:

```bash
!pip install opencv-python numpy matplotlib
