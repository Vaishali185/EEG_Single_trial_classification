# EEG_Single_trial_classification

Overview 

This repository contains my work on Single-Trial EEG Classification, where I focused on single trial classification of human brain states using Event-Related Potential (ERP) and brain connectivity features extracted from EEG data. The project is part of my thesis: "Single-Trial EEG Classification to Read Human Brain States," where I applied machine learning models to EEG data from normal and schizophrenia subjects to distinguish between target and distractor trials of Auditory oddball paradigm. 

The project demonstrates my skills in data analysis, signal processing, and machine learning. 

Key Highlights 

Data Analysis: Preprocessing and feature extraction from EEG data using ERP and connectivity measures. 

Machine Learning: Implementing multiple classifiers for single trial classification. 

Tools Used: Python, Pandas, NumPy, Scikit-learn, Seaborn, Plotly, MATLAB. 

Repository Structure 

ERPNew.ipynb: Notebook focused on extracting and analyzing ERP features from EEG recordings. 

ClassificationAlgorithNew.ipynb: Notebook that computes brain connectivity features, including measures like degree, clustering coefficient, and path length, from EEG data. 

Datasets 

The data used in this project includes EEG recordings from: 

54 normal subjects 

54 schizophrenia subjects 

Each subject performed an auditory oddball task with standard, target, and distractor tones. The notebooks preprocess the data, extract features, and prepare it for classification using machine learning models. 

Key Features 

1. ERP Features: 

Extracted from specific EEG channels (Fz, Cz, and Pz). 

Peak amplitude and latency of N100, P200, N200, and P300 events are extracted. 

2. Connectivity Features: 

Extracted using the Brain Connectivity Toolbox in MATLAB. 

Includes network measures such as degree, clustering coefficient, characteristic path length, and modularity. 

Machine Learning Models 

Both feature sets are used to train several classifiers: 

Logistic Regression 

Random Forest 

SVM 

K-Nearest Neighbors 

Decision Tree 

The models are evaluated using nested cross-validation, and the performance is compared across different feature sets. 

Requirements 

The project requires the following Python libraries: 

numpy 

pandas 

scikit-learn 

matplotlib 

seaborn 

plotly 

scipy 

Additionally, MATLAB is used to compute the connectivity matrices for the Connectivity Features notebook. 

Results 

The classification performance improves when using connectivity features compared to ERP features, especially when applied to larger groups of subjects (54 normal and schizophrenia subjects). 

 
