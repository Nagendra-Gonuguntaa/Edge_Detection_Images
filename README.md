# Edge Detection Comparison Project

## Overview

This project compares various edge detection algorithms using Python and popular libraries like OpenCV and scikit-image. The implemented methods are evaluated visually and quantitatively to identify their strengths and use cases.

## Edge Detection Methods

1. **Sobel**
2. **Canny**
3. **Laplacian**
4. **Prewitt**
5. **Roberts**

## Project Structure

- **load\_and\_display\_image()**: Loads and displays an image.
- **apply\_sobel()**: Implements Sobel edge detection.
- **apply\_canny()**: Implements Canny edge detection.
- **apply\_laplacian()**: Implements Laplacian edge detection.
- **apply\_prewitt()**: Implements Prewitt edge detection.
- **apply\_roberts()**: Implements Roberts edge detection.
- **visualize\_results()**: Displays the original image alongside edge-detected outputs for comparison.



## Requirements

- Python 3.x
- Libraries:
  - OpenCV
  - scikit-image
  - NumPy
  - Matplotlib
  - scikit-learn (optional, for evaluation metrics)

## Usage

1. Place your test image in the project directory.
2. Use the `load_and_display_image()` function to load the image.
3. Apply the edge detection methods to generate results:
   ```python
   sobel_result = apply_sobel(image)
   canny_result = apply_canny(image)
   laplacian_result = apply_laplacian(image)
   prewitt_result = apply_prewitt(image)
   roberts_result = apply_roberts(image)
   ```
4. Visualize results with `visualize_results()`:
   ```python
   methods_results = [sobel_result, canny_result, laplacian_result, prewitt_result, roberts_result]
   methods_names = ['Sobel', 'Canny', 'Laplacian', 'Prewitt', 'Roberts']
   visualize_results(image, methods_results, methods_names)
   ```


## Key Features

- Visual comparison of edge detection techniques.
- Quantitative evaluation (optional).
- Modular functions for extensibility.

##

---

For any questions or collaboration, reach out at [nagendra4career@gmail.com](mailto\:nagendra4career@gmail.com).


