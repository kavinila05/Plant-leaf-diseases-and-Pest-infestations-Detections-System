# Plant-leaf-diseases-and-Pest-infestations-Detections-System
An intelligent agriculture monitoring system that uses CNNs to monitor and automatically detect plant leaf disease and pest infestations.

## 🚜 Problem Statement

Traditional agricultural monitoring methods rely heavily on **manual inspection** and **experience-based decision making**, which are:
- Time-consuming
- Error-prone
- Inefficient for large-scale farming

Early detection of **plant diseases, pest attacks, and adverse soil conditions** is critical to improving crop yield, reducing pesticide usage, and ensuring sustainable agriculture.

---

## 🎯 Project Objectives

- Monitor **temperature, humidity, and soil moisture** in real time  
- Detect **plant leaf diseases** using CNN-based image classification  
- Identify **pest infestations** from images
   

---

## 🧠 System Overview

**Image Processing & Deep Learning Module**
   - CNN-based disease and pest classification
   - Trained on Kaggle plant disease and pest datasets
   - Achieved ~96–98% accuracy
---

## 💻 Software Stack

- Python 3
- TensorFlow & Keras
- OpenCV
- NumPy

---

## 🧪 Deep Learning Models

The following architectures were analyzed and compared:

- VGG-16
- ResNet-50
- Inception
- AlexNet
- **Proposed Optimized CNN Model**

### 📊 Performance Summary

| Model | Test Accuracy |
|------|---------------|
| VGG-16 | 82.75% |
| AlexNet | 90.68% |
| ResNet-50 | 98.73% |
| Inception | 99.98% |
| **Proposed CNN** | **96–98%** |

The proposed CNN achieves **high accuracy with lower computational complexity**, making it suitable for **edge deployment on Raspberry Pi**.

---

## 📸 Image Preprocessing

To enhance model robustness:
- HSV color-space conversion
- Leaf segmentation
- Noise reduction
- Normalization
- Data augmentation (rotation, flip, zoom, contrast)

These steps significantly improve generalization under real-world conditions.

---



## Authors

 Kavinila_V

---

## 🔮 Future Scope

  - Real-time camera-based continuous monitoring
  - Sensors and IoT integration
  - Information transmission
  - Drone-based field inspection
  - Predictive disease outbreak analysis
  - Integration with mobile applications
  - AI-driven irrigation and pesticide control

---

## 📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this work with proper citation.


