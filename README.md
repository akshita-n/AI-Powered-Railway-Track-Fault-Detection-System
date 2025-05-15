# 🚆 Railway Track Fault Detection

This repository contains a deep learning-based solution to automatically detect faults in railway tracks using object detection and image classification models. The project aims to enhance railway safety by identifying critical issues such as cracks, missing bolts, and misplaced clips from track images.

## 🧠 Models Used

The solution integrates both object detection and classification techniques:

### 🔍 Object Detection
- **YOLOv8**: Lightweight and real-time detector used to localize and label track defects.
- **Faster R-CNN**: Two-stage detector offering higher accuracy, used for comparison and performance benchmarking.

### 🖼️ Image Classification
- **InceptionV3**: Applied for transfer learning to classify cropped track segments based on detected faults.
- **ResNet50**: Utilized to compare classification accuracy with InceptionV3 using residual learning techniques.

---

## 📁 Dataset

The dataset contains annotated railway track images categorized into:
- **Crack**
- **Bolt Missing**
- **Clip Missing**
- **Normal**

Annotations for object detection models follow the respective formats:
- YOLOv8: YOLO format (`.txt` files)
- Faster R-CNN: Pascal VOC or COCO-style XML/JSON format

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/railway-track-fault-detection.git
cd railway-track-fault-detection

