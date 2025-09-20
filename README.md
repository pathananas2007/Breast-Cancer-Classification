# Breast Cancer Classification Using KNN & SVM

**Author:** @pathananas2007  
**Dataset:** Built-in scikit-learn Breast Cancer dataset  
**Course:** IBM Machine Learning with Python (Coursera)  

---

## Project Overview
This project applies classification models to predict whether breast tumors are **benign** or **malignant**. The notebook implements:

- Data loading and exploration  
- Feature scaling and preprocessing  
- Gaussian noise injection to test model robustness  
- Training and evaluation using:  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  
- Performance evaluation with:  
  - Accuracy scores  
  - Classification reports  
  - Confusion matrices  
- Visualizations of feature comparisons (original vs noisy) and confusion matrices  
- Comparison of training vs testing performance  

This project was completed as part of the IBM Machine Learning with Python course on Coursera. It demonstrates hands-on application of classification models for predicting breast cancer.

---

## Dataset
The dataset is included in **scikit-learn**. It contains:

- 30 numeric features about tumor characteristics  
- Labels: `0 = benign`, `1 = malignant`  
- Target names: `['malignant', 'benign']`  
- No external data download is required  

---

## Project Visualizations

### Feature Noise Comparison
![Feature Noise Comparison](images/plots.png)

### Confusion Matrices (Testing Data)
![Testing Confusion Matrices](images/plot_confusion_matrices.png)

### Overall Performance Comparison
![Overall Performance](images/overall_performance.png)

### Confusion Matrices (Training Data)
![Training Confusion Matrices](images/plot_confusion_matrices_training.png)

### Training vs Testing Accuracies
![Training vs Testing Accuracy](images/training_vs_testing_accuracy.png)

---

## Installation
Clone this repository:

```bash
git clone https://github.com/pathananas2007/Breast-Cancer-Classification.git
cd Breast-Cancer-Classification
