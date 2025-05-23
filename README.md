# Traditional Image Processing Tutorials

This repository documents my learning process in image processing, featuring beginner-to-intermediate level exercises implemented in Python using NumPy, SciPy, and Matplotlib. Each script reflects a core concept I explored through hands-on experimentation.

## 📂 Contents

### 🟢 1. Counting Peas (`counting_peas.py`)
Detects and counts small round objects (e.g. peas) from a desk image using image preprocessing, contour detection, and morphological operations.

Techniques used:
- Grayscale conversion
- Thresholding
- Morphological opening
- Contour detection and counting

---

### 🌀 2. Image Transforms (`dft_transform.py`)
Applies a manual 2D Discrete Fourier Transform (DFT) and inverse DFT to visualise frequency components and reconstruct grayscale images.

Techniques used:
- 2D basis image construction
- Forward and inverse DFT (with NumPy)
- Frequency domain visualisation
- Reconstruction with RMSE comparison

---

### ➕ 3. Convolution Filters (`convolution_filters.py`)
Implements basic spatial convolution filters to detect horizontal and vertical gradients in a simple binary image.

Techniques used:
- Custom filter kernel design
- 2D convolution with `scipy.signal.convolve2d`
- Edge detection using gradient kernels

---
## 🧠 About This Project

These scripts were created as part of my self-guided learning in traditional image processing. Each file is focused and minimal to help reinforce core concepts through code.
