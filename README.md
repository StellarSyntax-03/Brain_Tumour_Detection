# Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision
# Object Detection with YOLO v3 & TensorFlow

This project implements **YOLO v3 object detection** in TensorFlow.  
Unlike simple classification models that only tell you *what* is in an image, object detection also tells you *where* the objects are located. YOLO (You Only Look Once) is one of the fastest and most accurate algorithms for this task, making it perfect for real-time applications.

---

## 🚀 Features

- Full YOLO v3 architecture with **Darknet-53 backbone**
- Multi-scale detection heads for detecting small, medium, and large objects
- Pre-trained weight loading from original Darknet `.weights` files
- Post-processing with **Non-Maximum Suppression (NMS)** to remove duplicate boxes
- Utility scripts for:
  - Loading and preprocessing images
  - Reading class labels (e.g., COCO dataset)
  - Drawing bounding boxes and labels on images
- Ready-to-run demo with sample images

---

## 📦 Requirements

Make sure you have the following installed:

- Python 3.x  
- `tensorflow`  
- `numpy`  
- `Pillow`  
- `opencv-python`  
- `seaborn`  
- `IPython`

Install dependencies with:

```bash
pip install tensorflow numpy pillow opencv-python seaborn ipython
