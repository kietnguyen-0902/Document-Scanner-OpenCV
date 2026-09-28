# Document Scanner & Text Block Segmentation 📄

A complete Computer Vision pipeline built with Python and OpenCV to automatically scan documents from raw images, correct perspective distortion, and segment textual content into bounding boxes.

## 🚀 Core Features
1. **Document Boundary Detection:** Uses Canny edge detection and Contour approximation to locate the 4 corners of the document in the image.
2. **Perspective Transformation:** Applies a 4-point perspective warp to flatten the document, simulating a top-down scanned view.
3. **Adaptive Binarization:** Handles uneven lighting and shadows using Gaussian Adaptive Thresholding.
4. **Text Block Segmentation:** Employs morphological operations (specifically Dilation with horizontal kernels) to merge individual characters into cohesive text blocks and paragraphs.

## 🛠️ Technologies
- Python 3
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## 📂 Repository Structure
- `Document_Scanner_Pipeline.ipynb`: The main executable Jupyter Notebook with step-by-step visual outputs.
- `images/`: Sample images for testing the pipeline. The notebook will automatically download `image_1.jpg` if run locally without the repository.

## 📊 Sample Output
*(You can upload a screenshot of your final output image here and link it)*
