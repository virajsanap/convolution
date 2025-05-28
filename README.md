# 🧠 Image Convolution from Scratch

This project demonstrates how to manually implement 2D convolution operations on grayscale and RGB images using **NumPy**, without relying on deep learning or computer vision libraries like OpenCV or PyTorch.

It’s a compact, educational notebook for anyone looking to understand the **fundamentals of image processing** and how common filters (like Sobel, Laplacian, and Gaussian blur) work under the hood.

---

## 📌 What You'll Learn

- How 2D convolution works (from scratch using NumPy)
- The role of different kernels: sharpening, edge detection, blurring, etc.
- How convolution behaves differently on grayscale vs RGB images
- Visualization techniques to make the effect of kernels more clear
- Performance tips and clean code structure

---

## 🧪 Supported Kernels

| Operation        | Kernel Matrix Example |
|------------------|------------------------|
| **Sobel X**       | `[[-1, 0, 1], [-2, 0, 2], [-1, 0, 1]]` |
| **Sobel Y**       | `[[-1, -2, -1], [0, 0, 0], [1, 2, 1]]` |
| **Laplacian**     | `[[0, -1, 0], [-1, 4, -1], [0, -1, 0]]` |
| **Sharpen**       | `[[0, -1, 0], [-1, 5, -1], [0, -1, 0]]` |
| **Gaussian Blur** | `(1/16) * [[1,2,1],[2,4,2],[1,2,1]]`    |
| **Emboss**        | `[[-2,-1,0],[-1,1,1],[0,1,2]]`          |

---

## 🚀 How to Use

1. Clone or download the repo
2. Install dependencies (standard NumPy, PIL, matplotlib)
3. Open the `Convolution.ipynb` notebook
4. Run each cell and explore the outputs
5. Customize the kernel and image as needed

```bash
pip install numpy pillow matplotlib
