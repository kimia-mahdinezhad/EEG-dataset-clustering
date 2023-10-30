
# Fundamentals of Computational Intelligence Course Project

## Introduction
This document presents the comprehensive project I undertook as part of my university program's "Fundamental of Computational Intelligence" course. The project consists of three phases, each with specific objectives, related to the analysis and classification of EEG signals to detect seizures in epileptic patients. Below, I provide a summary of the key aspects of the project and the topics I explored during the course.

### Course Topics Covered
Throughout the course, I gained knowledge in the following areas of computational intelligence:

- Unsupervised Learning
- Decision Trees
- Support Vector Machines
- Perceptron
- Multilayer Perceptron
- Convolutional Neural Networks (CNNs)
- Ensemble Classifiers

## Phase 1 - Seizure Detection

### Project Description
In this initial phase of the project, the primary goal was to develop an intelligent system for detecting seizures in epileptic patients using EEG signals. This phase was divided into two sub-projects:

#### Data Preprocessing and Loading
The project began with creating a data loading and preprocessing pipeline. The dataset provided contained 500 signal segments, each 23.6 seconds long, sampled at 173.61 Hz. The data files were divided into five different groups, each with 100 segments. Proper data handling and preprocessing were essential to ensure efficient data access.

#### Feature Engineering
The subsequent step involved extracting essential features from the EEG signals. Feature engineering is crucial for building effective intelligent systems. I was tasked with implementing at least 15 features from three different categories, which included:
- Statistics
- Innovative
- Entropies
- LBP-based features
- Time domain
- Frequency Domain

#### Classification of Signals
Once the features were extracted, the project focused on classifying the signals into seizure and non-seizure categories. I implemented three different classification algorithms (SVM, Random Forest, and KNN) and evaluated their performance using k-fold cross-validation with k=5. I tested the impact of changing class parameters, algorithm parameters, input data normalization, and reported key evaluation metrics, including accuracy, precision, recall, and confusion matrices.

## Phase 2 - Feature Selection and Segmentation

#### Feature Evaluation and Selection
The second phase of the project centered on feature selection. I implemented a feature selection method that considered two key aspects:
- How well each feature can differentiate data individually, using a decision tree classifier.
- How different each feature is from the rest, evaluated through correlation metrics.

The goal was to identify and select the most informative features. This phase required combining the two metrics to determine the most relevant features. The selected features and the feature selection procedure were reported, emphasizing the significance of chosen features.

#### Improving Accuracy with Segmentation
In this part, I explored methods to enhance the accuracy and speed of the model by employing segmentation. The data was divided into different segments, and the previous classification system was trained on each segment. During testing, the system determined the appropriate subsystem based on the input data segment, resulting in a unified system for seizure diagnosis.

#### Evaluation with Different Problems
I selected three 2-class modes and one 3-class mode, as suggested by the course guidelines, to evaluate the project's performance. The evaluation encompassed different scenarios to assess the model's versatility and robustness.

## Phase 3 - Further Information
For details about the third phase of the project, please refer to the [Injection-Project](https://github.com/kimia-mahdinezhad/Injection-Project) repository, where you can find additional information and resources related to the project's continuation.
