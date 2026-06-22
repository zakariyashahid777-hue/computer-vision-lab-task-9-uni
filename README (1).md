# CV Lab Task 09: Content-Based Image Retrieval (CBIR)

This repository contains the implementation of **Content-Based Image Retrieval (CBIR)** techniques as part of the Computer Vision Lab Task 9. The project explores different methods to retrieve similar images from a dataset based on their visual content.

## Project Overview

The task involves two main approaches for image retrieval:
1.  **Color Histogram Matching**: Representing images as color histograms and using distance metrics (like Correlation or Intersection) to find matches.
2.  **Structural Similarity / Feature Extraction**: Processing images to extract features that represent structural or semantic content for more robust retrieval.

## Notebooks Included

*   **CBIR_Color_Histogram.ipynb**: 
    *   Implements a retrieval system based on **Color Histograms**.
    *   Uses OpenCV to calculate histograms for images in the dataset.
    *   Compares a query image against the dataset and returns the top matches.
*   **CBIR_Structural_Similarity.ipynb**:
    *   Explores more advanced feature scanning and similarity measures.
    *   Processes images into a common format for comparison.
*   **Miscellaneous.ipynb**:
    *   A scratchpad/template for further experimentation.

## Requirements

To run these notebooks, you need the following Python libraries installed:
*   `opencv-python`
*   `numpy`
*   `matplotlib`
*   `tqdm`

## How to Use

1.  Open any of the `.ipynb` files in Jupyter Notebook or VS Code.
2.  Ensure your image dataset path is correctly set in the code (e.g., the directory containing your images).
3.  Run the cells to see the retrieval results for query images.

---
**Repository**: [CV-Lab-Task-09]  
**Author**: Zakariya Shahid 
