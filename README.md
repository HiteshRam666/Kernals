# 🖼️ Image Processing with Kernels using OpenCV

Welcome to the **Image Processing with Kernels** notebook! This project explores different types of kernels (or filters) used in image processing to perform operations like edge detection, sharpening, and blurring using OpenCV in Python.

## 📂 Table of Contents

- [Introduction](#introduction)
- [Edge Detection Kernel](#edge-detection-kernel)
- [Sharpening Kernel](#sharpening-kernel)
- [Blurring Kernel](#blurring-kernel)
- [Requirements](#requirements)
- [How to Run](#how-to-run)

## 📝 Introduction

Kernels are essential components in image processing used to apply various effects to images. In this notebook, we explore how to use different kernels to modify images for tasks such as:
- **Edge Detection** 🕵️
- **Image Sharpening** ✨
- **Image Blurring** 🌫️

Each section demonstrates the implementation of these operations with corresponding code and visual outputs.

## 🔍 Edge Detection Kernel

In this section, we apply the **Sobel filter** to detect edges in an image. This is useful in identifying object boundaries and features within an image.

```python
sobel_vertical = np.array([[+1, +2, +1],
                           [ 0,  0,  0],
                           [-1, -2, -1]])
```

## ✨ Sharpening Kernel

Here, we use a sharpening kernel to enhance the details in an image. This operation is helpful in emphasizing textures and making the image more crisp.

```python
sharp = np.array([[ 0, -1,  0],
                  [-1,  5, -1],
                  [ 0, -1,  0]])
```

## 🌫️ Blurring Kernel

In the final section, we demonstrate how to blur an image using both a simple blur kernel and a Gaussian blur kernel. Blurring is often used to reduce noise or create artistic effects.

```python
blur = np.array([[1/9, 1/9, 1/9],
                 [1/9, 1/9, 1/9],
                 [1/9, 1/9, 1/9]])
```

## ⚙️ Requirements

To run this notebook, you need the following dependencies installed:

- `numpy`
- `matplotlib`
- `opencv-python`

You can install these using pip:

```bash
pip install numpy matplotlib opencv-python
```

## 🚀 How to Run

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the `Kernals.ipynb` notebook in Jupyter Notebook or any compatible editor.
4. Run the cells to see the kernel operations in action!

Enjoy exploring the world of image processing with OpenCV! 🎉
