# Gesture Recognition with CNNs and Transfer Learning

## Overview

This project explores **deep learning approaches for hand gesture recognition**, focusing on the comparison between training a **baseline CNN from scratch** and applying **transfer learning** with a pretrained AlexNet model.  
The system classifies hand images into multiple gesture categories and demonstrates the advantage of using pretrained feature extractors in computer vision tasks.  
<img width="500" height="500" alt="gesture" src="https://github.com/user-attachments/assets/2c379b12-47de-4d8d-982c-0877da41c239" />

## Approach
- Built a **baseline CNN** for multi-class hand gesture classification.  
- Implemented **transfer learning** using **AlexNet** as a frozen feature extractor.  
- Designed and trained a **custom classification head** on top of extracted features.  
- Compared model performance on training, validation, and test sets.  

## Results
- **Baseline CNN**: 85.4% test accuracy  
- **AlexNet + custom head**: 93.9% test accuracy  
- Transfer learning improved performance by **+8.5%**, with better generalization and reduced training time.  

## Tools & Frameworks
- **PyTorch**  
- **CNN architectures**  
- **Transfer Learning (AlexNet)**

## Academic Note
This project was completed as part of my course lab project 
The code and results are provided for **portfolio and demonstration purposes only**. Redistribution or reuse for coursework is not permitted.

