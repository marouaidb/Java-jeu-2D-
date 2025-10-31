#  Country Classification Using Machine Learning-

## Overview
This project applies supervised machine learning techniques to classify countries as Developed or Developing using indicators from a dataset produced by the World Health Organization (WHO).
It focuses on feature-space analysis, model comparison, and visualization of decision boundaries to evaluate how well different algorithms can separate the two classes.

## Objectives
- Assess whether selected indicators allow clear class separation.
- Compare the performance of different machine learning models.
- Analyse and visualize the decision boundaries for each approach.

## Methods

**Models implemented:**
- K-Nearest Neighbours (k-NN)
- Support Vector Machine (RBF kernel)
- Decision Tree
- Random Forest

**Preprocessing and evaluation:**
- Feature selection
- Normalization & scaling.
- Train/test split
- Evaluation using classification probability , ROC curves and and AUC computation.

## Results
- The dataset is **not perfectly linearly separable**; some regions show strong overlap.
- The Random Forest achieved the most stable and consistent decision regions.
- The Linear SVM performed correctly but showed the limitations of linear separation.
- Models were trained and evaluated on the same normalized feature space.

## Key Takeaways
-> Experience with data normalization, feature engineering, and model tuning.
-> Understanding of class overlap and decision boundaries in multi-feature datasets.
-> Ability to compare and evaluate several classical machine learning algorithms on real-world data.

