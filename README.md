## EEG Classification Project
### Introduction
This project focuses on the classification of electroencephalogram (EEG) signals to identify different states of brain activity. By applying machine learning and signal processing techniques, we aim to accurately categorize EEG data into predefined categories, such as different levels of sleep stages, cognitive tasks, or emotional states. This analysis has implications for medical diagnostics, brain-computer interfaces (BCIs), and understanding neurological conditions.

### Project Overview
The project utilizes EEG data sets to develop and test classification models. These models are designed to distinguish among various conditions or tasks by analyzing the electrical activity recorded from the scalp. The project explores several machine learning algorithms and aims to optimize preprocessing, feature extraction, and classification techniques to improve accuracy and efficiency.

### Data
 This dataset contains EEG recordings from patients with epilepsy. It includes 
various seizure types and non-seizure data.
https://physionet.org/content/chbmit/1.0.0/

### Method
#### Data Preprocessing:

A low-pass filter is applied to each EEG signal to reduce noise. The filter's cutoff frequency is set to 50 Hz, assuming a sampling frequency of 250 Hz.
#### Feature Extraction and Dimensionality Reduction:

Features are extracted from the EEG signals using techniques like wavelet transform and Principal Component Analysis (PCA) for dimensionality reduction.
The dataset is split into training, validation, and test sets for model training and evaluation.
#### Model Training and Evaluation:

A Long Short-Term Memory (LSTM) neural network is used for classification. The model is trained on the training set and evaluated on the validation and test sets.
Early stopping is implemented to prevent overfitting.
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score.
#### Visualization:

A confusion matrix is used to visualize the model's performance on the validation set.
The training and validation loss over epochs ar
