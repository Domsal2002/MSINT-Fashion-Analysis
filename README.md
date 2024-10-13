# Fashion MNIST Classification Case Study

## Overview
This project analyzes the performance of various classification algorithms on the Fashion MNIST dataset, focusing on both **binary** and **multi-class** classification tasks. The algorithms implemented include:

- **Logistic Regression**
- **k-Nearest Neighbors (KNN)**
- **Support Vector Machines (SVM)**
- **Decision Trees**

We experiment with hyperparameters for each algorithm and evaluate their performance using metrics such as **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC**.

## Dataset
The dataset consists of **70,000 grayscale images** (28x28 pixels) of fashion items across **10 categories**, such as T-shirts, trousers, and dresses. It serves as a more challenging alternative to the MNIST dataset of handwritten digits.  
[Access the Fashion MNIST Dataset on Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist)

## Project Structure

### Part 1: Binary Classification
- **Classes Used**: 
  - Class 0: T-shirt/top
  - Class 1: Trouser
- **Algorithms**: Logistic Regression, KNN, SVM, Decision Trees  
- **Best Model**: **SVM** with C=10, achieving **98.68% accuracy** and **99.92% ROC-AUC**.

### Part 2: Multi-Class Classification
- **Classes**: All 10 categories  
- **Algorithms**: Logistic Regression, KNN, SVM, Decision Trees  
- **Best Model**: **Logistic Regression** with C=1, achieving **84.38% accuracy**.

## Key Findings
- **Binary Classification**:  
  - SVM performed best, with excellent **class separation** indicated by the highest ROC-AUC.
  - Logistic Regression achieved the highest accuracy at **98.73%** with strong performance across all metrics.
  
- **Multi-Class Classification**:  
  - Logistic Regression outperformed other models with **84.38% accuracy** due to efficient optimization and handling of multi-class tasks.

## Recommendations
- **Logistic Regression**: Use for applications requiring **high accuracy**.
- **SVM**: Ideal when **class separation** and ranking tasks are priorities.

## Conclusion
This project provides insights into the strengths and weaknesses of different algorithms on image classification tasks. Logistic Regression and SVM emerged as top-performing models for binary and multi-class classification, respectively.

