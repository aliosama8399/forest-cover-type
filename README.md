# Forest Cover Type Prediction

## Overview

This project focuses on predicting forest cover types in the Roosevelt National Forest of northern Colorado using machine learning methods. The dataset is provided by [Kaggle](https://www.kaggle.com/competitions/forest-cover-type-prediction/data) and includes observations of 30m x 30m patches, with the goal of predicting one of seven forest cover types.

## Dataset

The dataset consists of observations in four wilderness areas. Forest cover types are represented by integers, with the following mapping:

- 1: Spruce/Fir
- 2: Lodgepole Pine
- 3: Ponderosa Pine
- 4: Cottonwood/Willow
- 5: Aspen
- 6: Douglas-fir
- 7: Krummholz

## Baseline Performance

Baseline performance is established using the following machine learning methods:

- KNN (K-Nearest Neighbors)
- Logistic Regression
- SVM (Support Vector Machine)
- Decision Tree Classifier
- Naive Bayes Classifier

For each method, a confusion matrix is plotted, and accuracy is calculated. These results are then visualized in a bar chart to establish a baseline.

## Feature Selection

Two approaches to feature selection are applied:

### Filter-Based Approach

- [Specify the filter-based approach used]
- Number of features vs accuracy is plotted for comparison.
- The baseline performance is shown as a constant dotted line with a distinct color.

### Wrapper-Based Approach

- Training and test sets are provided, along with the number of features and ML model.
- Two best-performing ML models from the Q1 stage are used for wrapper-based feature selection.
- Number of features vs accuracy is plotted for comparison.
- Baseline performance is shown as a constant dotted line with a distinct color.

## Random Forest and Ensemble Techniques

- Random Forest and two ensemble techniques are applied for improved performance.

## Self-Organizing Feature Map (SOFM) and PKI Strategy

- The best SOFM structure is determined using different configurations (6x6, 7x7, 8x8, 9x9, 10x10, 11x11, 12x12).
- PKI model is applied to show improvement through the PKI Strategy.
- Number of neurons vs accuracy is plotted, with the second improvement marked as a red dotted line.
- If a better result is obtained, it is used as the third improvement in the next phase.

## Project Structure

Explain the structure of your project and briefly describe the purpose of each directory.

