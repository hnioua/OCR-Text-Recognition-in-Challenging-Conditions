# OCR-Text-Recognition-in-Challenging-Conditions
---
Collaboration

Primary authors:

- Zakaraie Laaji
---
## 🧠 Project Overview
This project develops an OCR (Optical Character Recognition) solution that can detect and recognise text in difficult scenarios—noisy backgrounds, blur, and low contrast.  
It combines image-preprocessing pipelines with a comparative study of several OCR engines and deep-learning models.

---

## ⚙️ Features
- **Image Pre-processing** – noise reduction, deblurring, contrast enhancement, binarisation  
- **Engine Benchmarking** – Tesseract OCR, EasyOCR, and a custom TensorFlow model  
- **Performance Metrics** – precision, recall, and overall accuracy on degraded-image datasets  

---

## 🖼️ Image Processing Techniques

To enhance text visibility and improve OCR accuracy, the following image processing techniques are applied:

- **Grayscale Conversion** – simplifies the image for further processing  
- **Gaussian Blur Removal** – using filters to sharpen blurred text  
- **Noise Reduction** – via median or bilateral filtering  
- **Contrast Enhancement** – through histogram equalization and CLAHE (Contrast Limited Adaptive Histogram Equalization)  
- **Thresholding** – adaptive or Otsu thresholding for binarization  
- **Morphological Operations** – dilation, erosion, and opening to clean the text area  
- **Edge Detection** – optional use of Canny edge detector for region segmentation

---

## 🛠️ Tech Stack
| Layer            | Tools / Libraries                             |
|------------------|-----------------------------------------------|
| Language         | Python                                        |
| Image Processing | OpenCV, NumPy                                 |
| OCR Engines      | Tesseract OCR, EasyOCR                        |
| Deep Learning    | TensorFlow / Keras                            |
| Analysis & Viz   | Pandas, Matplotlib                            |

---
