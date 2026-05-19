# Brain Tumor MRI Classification Using Deep Learning

## Project Overview

This project uses deep learning and transfer learning techniques to classify brain MRI images into four categories:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The workflow compares multiple neural network approaches, beginning with baseline Artificial Neural Networks (ANNs) and progressing to convolutional neural network (CNN) transfer learning using VGG16.

The project demonstrates a complete medical imaging machine learning pipeline including preprocessing, augmentation, model comparison, evaluation, and fine-tuning.

---

## Objectives

- Build a multi-class MRI image classification model
- Compare ANN and CNN approaches
- Apply transfer learning using VGG16
- Improve generalization through fine-tuning and augmentation
- Evaluate performance using macro-F1 score and accuracy
- Present findings in a professional portfolio-ready format

---

## Dataset Overview

The dataset contains MRI brain scan images divided into four classes:

| Class | Description |
|---|---|
| Glioma | Brain tumor originating in glial cells |
| Meningioma | Tumor affecting brain membranes |
| Pituitary | Tumor affecting pituitary gland |
| No Tumor | MRI scans without visible tumor |

The project includes:
- dataset visualization
- preprocessing analysis
- class distribution analysis
- border cropping
- normalization
- augmentation pipelines

---

## Models Developed

### 1. Baseline ANN
- Fully connected neural network
- Flattened image input
- Serves as performance baseline

### 2. Optimized ANN
- Batch normalization
- Dropout regularization
- Weight decay optimization

### 3. VGG16 Frozen Transfer Learning
- Pretrained convolutional base
- Frozen feature extractor
- Custom classification head

### 4. VGG16 Fine-Tuned Model
- Partial layer unfreezing
- MRI-specific feature adaptation
- Strongest overall performance

### 5. VGG16 + Data Augmentation
- Rotation and crop augmentation
- Improved robustness testing
- Enhanced generalization strategy

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Evaluation Methods

The project evaluates models using:

- Accuracy
- Macro-F1 Score
- Confusion Matrix
- Classification Reports
- Validation Curves
- Test Performance Comparison

---

## Key Results

The best-performing model was the fine-tuned VGG16 architecture with a custom feedforward classifier head. Results showed that CNN-based transfer learning significantly outperformed flattened ANN models for MRI image classification.

The project also demonstrated the importance of:
- spatial feature extraction
- transfer learning
- preprocessing consistency
- balanced evaluation metrics

---

## Repository Contents

| File | Description |
|---|---|
| `Jake_Grolig_Brain_Tumor_Project.ipynb` | Full Jupyter notebook |
| `Jake_Grolig_Brain_Tumor_Project.html` | Exported HTML project report |
| `requirements.txt` | Python dependencies |

---

## View Full HTML Report

Click below to view the complete exported notebook:

[View HTML Report](./Jake_Grolig_Brain_Tumor_Project.html)

---

## Future Improvements

Potential future enhancements include:
- Grad-CAM explainability visualizations
- Additional CNN architectures
- External dataset validation
- Hyperparameter optimization
- Clinical deployment considerations

---

## Author

James (Jake) Grolig

Applied AI / Machine Learning Portfolio Project
