# 🧠 AAI TP3 – Understanding Convolution in AI & Image Processing

This project demonstrates the **manual implementation of 2D convolution filters** in Python as part of the **Artificial Intelligence and Applications (AAI)** module. The goal is to understand how convolution operates on images and why it's foundational in computer vision and AI.

---

## 📚 What Is Convolution?

**Convolution** is a mathematical operation used to extract spatial features from images. It involves sliding a small matrix (called a **kernel** or **filter**) over an image and computing a weighted sum at each position. This highlights patterns like:

- Edges
- Corners
- Shapes
- Textures

In **Artificial Intelligence**, especially in **Convolutional Neural Networks (CNNs)**, convolution is used to help models learn what parts of an image are important — from simple lines to complex objects.

---

## 🧠 Why It Matters

Convolutional layers are the backbone of most computer vision models. By applying filters over pixels, models can detect:

- **Edges** using gradient filters (like Sobel)
- **Blur/smoothness** using averaging filters
- **Sharpened details** using contrast-enhancing filters

Understanding how convolution works at the pixel level helps you appreciate what CNNs do internally — and builds intuition for designing better models.

---

## 🛠️ What This Project Covers

This notebook walks through:

1. Loading a grayscale image and converting it into a 2D array
2. Manually defining 3x3 filters (kernels) for different effects
3. Applying the convolution operation using nested loops (no OpenCV or deep learning libs)
4. Visualizing the **original vs. filtered images** using `matplotlib`

---

## 🔧 Libraries Used

- [`numpy`](https://numpy.org/) – for numerical computation and matrix handling  
- [`matplotlib`](https://matplotlib.org/) – for visualizing images  
- [`PIL`](https://pillow.readthedocs.io/) or `cv2` – for loading and converting images (optional)

---

## 👨‍💻 Author

Made by [@ab2gbl](https://ab2gbl-portfolio.vercel.app/)
Part of the M2 SDIA program at Université Constantine 2, for the Artificial Intelligence & Applications (AAI) module.

