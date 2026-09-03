Implemented Grad-CAM explainability to visualize chest X-ray regions contributing to pneumonia predictions.

X-ray
  ↓
CLAHE preprocessing
  ↓
ResNet18
  ↓
Prediction
  ↓
Grad-CAM
  ↓
Heatmap showing important regions

Developed a Python-based computer vision system to classify chest X-ray images as Normal or Pneumonia.
Applied image preprocessing and CLAHE contrast enhancement to improve relevant visual features in X-ray images.
Implemented ResNet18 transfer learning with PyTorch for automated chest X-ray classification.
Evaluated model performance using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC.
Designed an explainable AI pipeline using Grad-CAM to visualize image regions influencing model predictions.
Investigated the impact of image preprocessing on pneumonia classification performance.