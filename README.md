# 🖼️ SVD Image Compression Project

**Author**: Kaitlyn Kirt  
**Course**: CMOR 220  
**Term**: Spring 2024  
**Project**: Singular Value Decomposition (SVD) for Image Compression  
**Last Modified**: April 9, 2024  

---

## 📋 Overview

This project demonstrates how **Singular Value Decomposition (SVD)** can be used to compress grayscale images by approximating them with lower-rank matrices. It visualizes compression effects using different approximation factors and identifies the best rank to preserve a specified level of visual clarity.

---

## 📂 Files

- `Project9.ipynb`: Main Jupyter notebook that loads an image, converts it to grayscale, and applies SVD for compression.
- `image-2.jpg`: The input image used for testing compression (ensure it is placed in the same directory).
- `README.md`: Project overview and usage guide.

---

## 🔍 Techniques Used

- **Grayscale Conversion**: Transforming RGB to grayscale for simplicity and reduced complexity.
- **SVD Decomposition**: Breaking the image matrix into `U`, `Σ`, and `V` matrices.
- **Rank Approximation**: Determining optimal matrix rank to retain most image information with fewer components.
- **Compression Factor Visualization**: Comparing image clarity across various compression levels.

---

## 🛠️ Requirements

```bash
pip install numpy matplotlib
