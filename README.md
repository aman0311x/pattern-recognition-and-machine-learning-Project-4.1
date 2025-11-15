# EfficientNet-CBAM: Attention-Guided Brain Tumor Classification

## Overview
The human brain, an organ of unparalleled complexity, is susceptible to anomalous cell proliferation leading to tumor formation. Accurate and early diagnosis of brain tumors is critical for guiding therapeutic decisions and improving patient outcomes. Magnetic Resonance Imaging (MRI) provides exceptional soft-tissue contrast, making it the non-invasive gold standard for brain tumor detection.

Manual interpretation of MRI scans by radiologists is challenging due to subtle morphological differences between tumor types, variations in tumor size, shape, and location, and the large volume of images requiring analysis. These challenges make Computer-Aided Diagnosis (CAD) systems highly valuable for supporting clinical workflows.

This project presents a **novel attention-guided deep learning framework** for multi-class brain tumor classification, combining high accuracy with interpretability using Explainable AI (XAI) techniques.

---

## Features & Contributions
1. **Novel Attention-Guided Architecture**
   - Proposed **EfficientNet-CBAM**, integrating a Convolutional Block Attention Module (CBAM) into an EfficientNetB3 backbone.
   - Enhances feature discrimination by focusing on the most pathologically relevant regions in MRI scans.

2. **State-of-the-Art Performance**
   - Achieved **99.29% classification accuracy** on multi-class brain tumor datasets.
   - Comparative benchmarking against baseline models such as ResNet50, MobileNetV2, and EfficientNetB3.

3. **Explainable AI (XAI) Integration**
   - Implemented **HiResCAM** gradient-based visualization for heatmaps.
   - Provides visual explanation highlighting tumor regions influencing model predictions, improving clinical trust.

4. **Model Reliability & Confidence Analysis**
   - Visualization of prediction confidence scores.
   - Helps analyze correctly and incorrectly classified images, offering insights into model certainty.

---

## Dataset
The model is trained and validated on publicly available brain tumor MRI datasets, including:
- **Glioma**
- **Meningioma**
- **Pituitary Tumor**

> Ensure that the dataset is downloaded and organized into appropriate folders for training and validation.

---

## Tech Stack
- **Framework:** Python, TensorFlow, Keras
- **Core Libraries:** OpenCV, NumPy, Matplotlib, scikit-learn
- **Deep Learning Models:** EfficientNetB3, CBAM, ResNet50, MobileNetV2
- **XAI Tools:** HiResCAM

---

## Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/aman0311x/efficientnet-cbam-brain-tumor.git
cd efficientnet-cbam-brain-tumor
