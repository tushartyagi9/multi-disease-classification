# Multi-Label Lung Disease Classification 2024

Multi-label chest X-ray classification project focused on identifying 13 thoracic diseases from 29K+ images.

## Tech Stack
- Python
- PyTorch
- OpenCV
- NumPy
- Scikit-learn
- EfficientNet-B1
- Grad-CAM

## Approach
- Trained an EfficientNet-B1 model for 13-class multi-label thoracic disease prediction.
- Addressed class imbalance using oversampling, augmentation, and regularization.
- Used Grad-CAM visualizations to validate model attention against pathology regions.

## Results
- Mean AUC-ROC: **0.75**
- Best class AUC-ROC: **0.87** (Emphysema)
