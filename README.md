# Detection of Fractures on X-Ray Bone Images with Deep Learning Methods
This repository presents the implementation and experimental results of my undergraduate graduation thesis, focusing on the detection and localization of bone fractures in X-ray images using deep learning–based object detection methods.

**Project Overview**
- A custom X-Ray dataset was created by combining publicly available fractured and non fractured bone images from multiple sources.

- Fracture regions were manually annotated using bounding boxes, with " makesense.ai ".

- Data augmentation techniques were extensively applied to improve model robustness and generalization.

**Models & Methods**

The following state of the art object detection models were trained and evaluated under different dataset configurations:

- YOLOv8

- RT-DETR

- Faster R-CNN

- RetinaNet

Model performances were analyzed using standard evaluation metrics, including *Precision*, *Recall*, and *mAP@50*, with special attention to small and visually ambiguous fracture detection.

**Key Results**

*RT-DETR-X* achieved the best overall performance with an mAP@50 score of 72.9%.

*Transformer based* architecture demonstrated strong robustness against:

- Class imbalance

- Small-object detection challenges

- Complex anatomical structures

**Application Interface**

To improve usability and real world applicability, the best performing model was integrated into a lightweight Flask based desktop interface, enabling:

- Easy X-Ray image upload

- Real time fracture detection

- Visual localization of fracture regions

This interface bridges the gap between advanced AI models and practical clinical usage.

**Purpose & Impact**

This project aims to contribute to AI assisted medical imaging by providing an accessible and efficient fracture detection tool, designed to support clinical decision making especially in emergency settings and resource limited environments.

**Developed by**

Emir Kıvrak
Ege University
Department of Electrical & Electronics Engineering
