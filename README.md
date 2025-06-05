# FastSAM Segmentation & Visualization Notebook

This notebook runs **FastSAM** (Ultralytics) on a batch of images and visualizes segmentation results.

## 🔧 What It Does

- Loads a local FastSAM model (`FastSAM-x.pt`)
- Scans a folder (e.g. `/content/`) for images named `ex1.jpg`, `ex2.jpg`, ...
- For each image:
  - Runs FastSAM segmentation and object localization
  - Displays:
    - Original Image
    - Segmentation overlay with masks and bounding boxes
    - Combined binary segmentation mask
- Shows results in a **3-column layout** per image (1 row per image)
- Designed for **visual comparison across multiple images**

## Please note: the number of detected objects can be controlled by adjusting IoU and conf. 
