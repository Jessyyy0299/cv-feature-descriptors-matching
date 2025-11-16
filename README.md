# Classical Feature Descriptors and Matching (Computer Vision)

This repository contains a course exercise on **feature descriptors** and **feature matching** for the Yale Computer Vision class (CPSC 480/580).

> Author: **Jessy Xue**  
> Topic: Gradients, Histogram of Oriented Gradients (HOG), and SIFT feature matching.

---

## 🧠 Overview

The exercise focuses on building and understanding classical image descriptors and how they behave under different transformations. The main components are:

- Computing **image gradients**, magnitude, and orientation  
- Building a **hand-crafted orientation histogram** on small blocks  
- Using **HOG (Histogram of Oriented Gradients)** from `skimage.feature.hog`  
- Extracting **SIFT keypoints and descriptors** on:
  - original images  
  - rotated images  
  - affinely transformed images  
  - darkened images  
- Matching descriptors between image pairs and visualizing correspondences

All implementation and results are documented in the attached PDF report.

---

## 📄 Files

- `cv_feature_descriptors_exercise.pdf`  
  Contains:
  - Code snippets for gradient computation, HOG, and SIFT  
  - Visualizations of gradients and HOG maps  
  - Visualization of SIFT matches under rotation, affine transformation, and illumination changes

---

## 🛠 Techniques Demonstrated

- Gradient and orientation computation  
- Orientation histograms and HOG descriptors  
- SIFT keypoint detection and descriptor extraction  
- Descriptor matching with ratio test and cross-check  
- Visualization of feature correspondences

