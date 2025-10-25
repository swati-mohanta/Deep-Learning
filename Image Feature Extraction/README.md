# **Image Feature Extraction**

This repository demonstrates various image processing and feature extraction techniques using Python and OpenCV. Experiments include image arithmetic, thresholding, segmentation, blurring, edge detection, morphological operations, and sharpening.

---

## **Experiments Included**

1. **Image Arithmetic**

   * Perform addition and subtraction of two images.
   * Visualize original and resulting images.

2. **Bitwise Operations**

   * Convert images to binary and perform bitwise AND and OR operations.
   * Demonstrates masking and logical operations on images.

3. **Thresholding Techniques**

   * Global thresholding (Binary, Binary Inverted, Truncate, To Zero, To Zero Inverted).
   * Adaptive thresholding (Mean and Gaussian).
   * Otsu’s thresholding with and without Gaussian blur.

4. **Image Segmentation**

   * Segment an image using Otsu’s thresholding mask.
   * Visualize original, mask, and segmented images.

5. **Morphological Operations**

   * Apply erosion on binary images.
   * Demonstrate effects of morphological transformations.

6. **Blurring Techniques**

   * Average blur, Gaussian blur, and Median blur on images.
   * Comparison with original image to show smoothing effects.

7. **Adding Borders**

   * Apply different border types: Constant, Reflect, Replicate.
   * Observe how borders modify image edges.

8. **Edge Detection**

   * Apply Canny edge detection on grayscale images.
   * Visualize edges for image analysis.

9. **Sharpening**

   * Enhance image details using a sharpening kernel.
   * Compare original and sharpened images.

---

## **Libraries Used**

* `OpenCV (cv2)` – For image processing operations.
* `Matplotlib` – For displaying images and results.
* `NumPy` – For array and kernel operations.

---

## **How to Use**

1. Clone the repository:

   ```bash
   git clone <repository-link>
   ```
2. Place your images in the project directory.
3. Run the Python script:

   ```bash
   python image_feature_extraction.py
   ```
4. Visualize results for different experiments as plotted by Matplotlib.

---

**Note:**

* Ensure the image filenames in the script match the images in your folder.
* Recommended image sizes are at least 400x400 for better visualization.
