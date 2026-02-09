# Digit Recognizer — CNN with Error Analysis

This project presents a complete solution to the Kaggle **Digit Recognizer (MNIST)** competition using a **Convolutional Neural Network (CNN)** built with TensorFlow / Keras.

Rather than focusing solely on model complexity, the emphasis is on building a robust
and well-reasoned image classification pipeline that includes careful preprocessing,
realistic data augmentation, and systematic error analysis.

---

## Project Overview

- **Task:** Classify handwritten digits (0–9) from 28×28 grayscale images  
- **Dataset:** MNIST (via Kaggle Digit Recognizer competition)  
- **Model:** Convolutional Neural Network (CNN)  
- **Framework:** TensorFlow / Keras  
- **Evaluation:** Validation accuracy, confusion matrix, and error visualization  

---

## Key Features

- Clean preprocessing and pixel normalization  
- Realistic data augmentation (rotation, shift, zoom, shear)  
- CNN architecture with Batch Normalization and Dropout  
- Learning rate scheduling and early stopping  
- Detailed error analysis, including:
  - Visualisation of misclassified images  
  - Confidence analysis of incorrect predictions  
  - Confusion matrix to identify systematic confusions  

---

## Results

- Validation accuracy: **~99.3–99.5%**
- Strong generalization due to augmentation and regularization
- Remaining errors concentrated in visually ambiguous digits (e.g. 4 vs 9, 5 vs 8)

---

## Why Error Analysis Matters

Instead of relying on deeper or more complex models, this project demonstrates how
examining model failures can lead to meaningful improvements.

By analysing:
- where the model is wrong
- how confident it is when wrong
- which digits are most frequently confused

we gain insights that directly guide model refinement.

---

## Potential Extensions

- Model ensembling  
- Test-time augmentation (TTA)  
- Cross-validation-based training  
- Applying the same workflow to more challenging vision datasets  


---

## Final Note

This project is intended as a clear and reproducible example of a thoughtful approach
to image classification — balancing performance, interpretability, and analysis.

Feel free to explore, adapt, or build upon it.
