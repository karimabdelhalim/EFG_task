# Logo-inpainting
This project implements an image inpainting algorithm using the SIFT feature detector and the FLANN based matcher in OpenCV. The algorithm identifies the bounding box of a reference image within an input image, then inpaints that bounding box using the average color of the surrounding pixels.


To address this challenge, I implemented and tested three different methods:

1. **SIFT (Scale-Invariant Feature Transform)**
2. **OCR (Optical Character Recognition)**
3. **Removing Green Color**


   ### 1. SIFT (Scale-Invariant Feature Transform)
   **Results**:
- SIFT provided the most accurate and reliable results for the challenge.
### 2. OCR (Optical Character Recognition)
**Results**:
- OCR successfully removed logos from 6 out of 9 images.
- Although not perfect, it proved to be a useful technique for logo detection and removal.
