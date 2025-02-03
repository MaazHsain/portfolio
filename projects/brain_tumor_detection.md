---
layout: project
type: fyp
image: img/brain_tumor/thumbnail.png
title: "Revolutionizing Brain Tumor Detection with Deep Learning (FYP)"
date: 2024-09-01
published: true
labels:
  - Machine Learning
  - Artificial Intelligence
  - Python
  - Models
  - Deep Neural Networks
  - CNN
  - U-Net
  - VGG16
  - TensorFlow
  - Keras
  - OpenCV
  - Deep Learning
  - Medical Imaging
  - Brain Tumor Detection
  - AI in Healthcare
summary: "Project focuses on the development of a robust and accurate system for detecting brain tumors from MRI scans using advanced deep learning techniques. The core of the project leverages Convolutional Neural Networks (CNN) and U-Net models to achieve high precision in tumor identification and segmentation."
---

<div class="text-center p-4">
  <img width="500px" src="../img/brain_tumor/model_integration_pipeline.png" class="img-thumbnail" >
  <img width="500px" src="../img/brain_tumor/prototype_results.png" class="img-thumbnail" >
</div>

#### Overview ####
Detecting brain tumors is a critical step in early diagnosis and treatment planning, yet traditional methods often involve significant time and effort from medical professionals. This project aims to address these challenges with an automated system that leverages Convolutional Neural Networks (CNN) for classification and U-Net architectures for precise segmentation. By combining cutting-edge deep learning techniques, the system identifies and localizes tumors from MRI scans with remarkable accuracy, assisting healthcare practitioners in clinical decision-making.

---

#### The Technical Journey: A Three-Phase System ####
This system wasn't just built—it evolved through a meticulously designed pipeline. Here's a glimpse of the main phases that brought it to life:

<div class="text-center p-4">
  <img width="500px" src="../img/brain_tumor/mindmap.png" class="img-thumbnail" >
</div>

#### Data Preprocessing: Preparing the Images ####
To ensure consistent and effective model inputs, MRI scans underwent rigorous preprocessing:  
1. **Standardization**: All images resized to 224x224 for CNN and 256x256 for U-Net to align with model requirements.  
2. **Brain Isolation**: Algorithms cropped brain regions using contour detection, eliminating irrelevant background noise.  
3. **Image Augmentation**: Techniques like rotation and flipping enriched the dataset, enhancing model generalization.

<div class="text-center p-4">
  <img width="500px" src="../img/brain_tumor/augmentation.png" class="img-thumbnail" >
</div>

#### Model Implementation ####
1. **CNN for Classification**: Using a fine-tuned VGG16 model, the system classifies MRI scans as tumor-positive or tumor-negative, ensuring high recall rates to minimize false negatives.  
2. **U-Net for Segmentation**: A custom-built U-Net architecture pinpoints the exact tumor location, providing a visual overlay for clarity. The model employs Dice loss for enhanced accuracy in pixel-level predictions.  

<div class="text-center p-4">
  <img width="500px" src="../img/brain_tumor/classification_result.png" class="img-thumbnail" >
  <img width="500px" src="../img/brain_tumor/seg_results.png" class="img-thumbnail" >
</div>

#### Result Generation: Insights for Clinicians ####
The system produces intuitive and visually enriched results:
-  Overlay Visualization: Tumor regions are highlighted on MRI scans with red overlays and contours.
-  Heatmaps: Provide a color-coded intensity map of the tumor's location.
-  Large-Scale Automation: A batch-processing feature enables classification and segmentation of large volumes of MRI scans, optimizing efficiency in clinical workflows.

The solution is scalable, handling batch MRI scans from a directory. Each scan is processed, classified, segmented, and annotated with heatmaps, making it an invaluable tool for clinical applications requiring high throughput.

<div class="text-center p-4">
  <img width="500px" src="../img/brain_tumor/large_scale_results.png" class="img-thumbnail" >
</div>

---

#### Key Features ####
- **Efficient Pipeline**: Seamless integration of classification and segmentation for end-to-end automation.  
- **Scalability**: Designed to process hundreds of MRI scans efficiently in a single batch.  
- **Clinical Utility**: Visual overlays and heatmaps offer intuitive insights for healthcare professionals.  

---

#### Challenges and Insights ####
Building this system presented unique challenges, from managing imbalanced datasets to optimizing models for high precision. A pivotal realization was the importance of pre-trained networks like VGG16 and advanced architectures like U-Net in bridging the gap between raw MRI data and actionable medical insights.

---

#### Proud Achievements ####
-  Developed a scalable system capable of processing entire MRI folders with automated detection and segmentation.
-  Achieved precise tumor localization, aiding early diagnosis and treatment planning.
-  Designed a pipeline that could easily integrate into real-world healthcare environments.

---

#### Results
- Classification
<div class="text-center p-4">
  <img src="../img/brain_tumor/class_res.png" class="img-thumbnail" >
</div>

- Segmentation
<div class="text-center p-4">
  <img src="../img/brain_tumor/unet_res.png" class="img-thumbnail" >
</div>

---

#### Why This Matters ####
The automation of brain tumor detection is more than a technological advancement; it’s a step toward democratizing healthcare. By reducing diagnostic delays and increasing accuracy, this system empowers radiologists and clinicians, ultimately improving patient outcomes.

---

#### Final Thoughts ####
This project underscores the potential of AI in revolutionizing medical imaging. While it represents a leap forward in automating brain tumor detection, the journey doesn't end here. Future improvements could include incorporating 3D models and exploring multi-modal data to push the boundaries of accuracy and usability further.  

This experience not only strengthened my understanding of deep learning but also reinforced my belief in its capacity to address real-world challenges with transformative solutions.  
