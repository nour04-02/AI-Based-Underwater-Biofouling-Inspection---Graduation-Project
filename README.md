# AI-Based Underwater Biofouling Inspection

An AI system for detecting, classifying, and segmenting biofouling on underwater ship hulls using YOLOv8.

The goal is to reduce reliance on dangerous manual underwater inspections and provide consistent, data-driven assessment.

---

## Problem

Manual underwater inspections depend on human divers operating in hazardous conditions with poor visibility and strong currents.  
Biofouling increases fuel consumption, maintenance costs, and harms marine life.

---

## Approach

- **Biofouling Classification:**  
  Surfaces are classified into four levels: Clean, Light, Moderate, Heavy.

- **Biofouling Segmentation:**  
  YOLOv8 segmentation is used to localize fouling regions at pixel level.

- **Models Used:**  
  YOLOv8 Nano and YOLOv8 Small  
  Trained on 1,000 labeled underwater images.

---

## Technologies

- Python  
- YOLOv8 (Ultralytics)  
- PyTorch  
- OpenCV  
- NumPy  

---

## Notes

This project is part of an academic AI research and graduation project.
