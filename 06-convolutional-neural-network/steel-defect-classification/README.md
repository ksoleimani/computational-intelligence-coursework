# Convolutional Neural Network (CNN) — Transfer Learning

## Objective
Classify 6 types of steel surface defects using a custom CNN and a transfer-learning
model (MobileNetV2), and interpret their predictions with Grad-CAM.

## Topics
- Image Augmentation
- CNN Architecture (Conv2D, BatchNorm, MaxPooling)
- Transfer Learning (MobileNetV2)
- Grad-CAM Visualization
- Confusion Matrix & Classification Report
- Global Average Pooling

## Libraries
- NumPy
- Pandas
- Matplotlib
- Keras / TensorFlow
- scikit-learn
- Pillow

## Files
- steel_defect_cnn.ipynb

## Results
The custom CNN reached 47.41% test accuracy (overfit on training data), while the
MobileNetV2 transfer-learning model reached 99.63% test accuracy. Grad-CAM and a
confusion matrix were used to analyze failure modes — the most common confusion was
Rolled-in scale misclassified as Patches, and Inclusion defects went entirely
undetected (0.00 recall).
