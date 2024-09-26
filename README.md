# Cancer_cell_classification_using_Scikit_learn

This repository contains a google colab for classifying cancer cells as either benign or malignant using machine learning models from the scikit-learn library. The project utilizes the well-known Breast Cancer Wisconsin (Diagnostic) dataset, which is part of the scikit-learn datasets collection. The goal is to build, evaluate, and optimize a machine learning pipeline for accurate classification.

**Table of Contents**
  Project Overview
  Dataset
  Models
  Evaluation Metrics
  Results

**Project Overview**
The purpose of this project is to build a machine learning model to classify cancer cells using the Scikit-Learn library, focusing on the Gaussian Naive Bayes algorithm. The dataset used contains features computed from digitized images of fine-needle aspirate (FNA) of breast masses. The main objective is to predict whether the cancer is benign or malignant based on cell features such as radius, texture, perimeter, and area.

**Dataset**
The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset, which is included in scikit-learn. It consists of 30 features computed from the digitized images of breast tissue. The dataset has a total of 569 samples, where:

357 samples are benign (no cancer).
212 samples are malignant (cancer present).

**Features:**

The 30 features include:
Mean radius, mean texture, mean perimeter, mean area, mean smoothness, etc.
Standard error of radius, texture, perimeter, area, smoothness, etc.
Worst radius, worst texture, worst perimeter, worst area, and worst smoothness.
The target variable is a binary indicator of whether the tumor is malignant (1) or benign (0).

**Models
Gaussian Naive Bayes Model**

The Gaussian Naive Bayes algorithm assumes that the features follow a normal distribution, making it particularly effective for datasets with continuous features. It works well for this classification task as most features in the Breast Cancer dataset are numerical.

**Results**
The Gaussian Naive Bayes model achieved the following performance metrics:

  Accuracy: ~90%
  Precision: ~90%
  Recall: ~94%
  F1-Score: ~92%
Refer to the google colab for detailed evaluation results and visualization of model performance.
