# Reproducing Research Papers on Computer Vision

Welcome to the **Computer Vision Reproducibility Repository**! This repository is dedicated to reproducing key research papers in the field of computer vision. The primary goal is to replicate and validate the results presented in these papers, making the findings more accessible and applicable.

## Objectives
- Reproduce and implement algorithms from well-known research papers in computer vision.
- Validate the claims made in these papers by testing their approaches on publicly available datasets.
- Share insights, challenges, and improvements encountered during the reproduction process.

## Papers to Reproduce
This project implements the **"Computer Vision System for Speed Limit Traffic Sign Recognition"** paper using OpenCV and Deep Learning. It detects and recognizes speed limit signs using a **shape-based method** for detection and a **CNN for digit recognition**.

## 📖 **Paper Reference**
> **Adelina D. Salimullina, Dmitry O. Budanov,**  
> *Computer Vision System for Speed Limit Traffic Sign Recognition*, IEEE Conference, 2022.  
> [🔗 Read Paper](https://ieeexplore.ieee.org/document/9755744) (Requires access)

---

## 🏗 **Project Overview**
The system consists of **two main stages**:
1. **Traffic Sign Detection (Shape-Based Approach)**
   - Detects circular speed limit signs using OpenCV.
   - Uses **Gaussian blur, edge detection, Hough Circle Transform, and contour detection**.

2. **Traffic Sign Recognition (CNN-Based Approach)**
   - Extracts and recognizes digits from detected signs.
   - Uses a **Convolutional Neural Network (CNN)** trained on **MNIST and GTSRB datasets**.

