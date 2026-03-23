# 🦴 Hand Bone Detection using YOLOv8 (KerasCV)

## 📌 Overview

This project implements an object detection model to detect and classify hand bones using **YOLOv8 with KerasCV**.

The model identifies the following bone types:

* Carpal
* Metacarpal
* Phalanges
* Radius
* Ulna

---

## 🚀 Features

* Custom dataset from Roboflow
* YOLOv8-based detection model
* Data augmentation using KerasCV
* Non-Max Suppression (NMS) for clean predictions
* Training + inference pipeline included

---

## 🧠 Model Details

* Backbone: YOLOv8 Small (yolo_v8_s_backbone)
* Input size: 640x640
* Loss:

  * Classification: Binary Crossentropy
  * Box: CIoU

---

## 📂 Dataset

Dataset obtained from Roboflow:

* 458 images
* Train: 88%
* Validation: 9%
* Test: 3%

---

## 🛠️ Installation

```bash
pip install roboflow keras-cv tensorflow opencv-python
```

---

## ▶️ How to Run

1. Open the notebook:

jupyter notebook hand_bone_detection.ipynb

2. Run all cells step-by-step


## 📌 Future Improvements

* Improve accuracy with larger dataset
* Deploy model to Android (TFLite)
* Real-time detection system

---

## 👨‍💻 Author

Het Brahmbhatt
