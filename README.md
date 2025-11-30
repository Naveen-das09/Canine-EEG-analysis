# EEG Analysis Pipeline

This repository contains a machine learning pipeline for EEG analysis. The project focuses on preprocessing, feature extraction, and classification of EEG signals. 
The pipeline is implemented in a Python Jupyter Notebook and includes all relevant processes to analyze EEG data effectively.

## Introduction

EEG (Electroencephalography) is a method to record electrical activity of the brain. This project aims to develop a machine learning pipeline to preprocess, extract features, and classify EEG signals. The pipeline can be used for various applications, including cognitive neuroscience research and medical diagnosis.

## Features

- **Data Preprocessing:** Includes noise filtering, artifact removal, and normalization.
- **Feature Extraction:** Extracts relevant features from the EEG signals for classification.
- **Dimensionality Reduction:** Utilizes techniques such as PCA for reducing the feature space.
- **Classification:** Implements various machine learning models to classify EEG signals.
- **Visualization:** Provides visualization of the EEG signals and the results of the classification.


Contents / What’s in this repo

Olfaction_EEG_anlaysis.ipynb — Main analysis notebook: end-to-end pipeline (preprocessing → feature extraction → visualization → modelling). 
GitHub

experiment_data_segment_1.csv, experiment_data_segment_2.csv — Example EEG data segments used in the notebook. 
GitHub

Models/ — Saved model artifacts (trained classifiers / pickles). 
GitHub

analysis_plots/ — Generated figures used for inspection and reporting. 
GitHub

requirements.txt — Python dependencies needed to run the notebook. 
GitHub

Quick overview

This project demonstrates a typical EEG ML workflow:

Load/inspect raw EEG segments (CSV files included as example data).

Preprocess signals (filtering, de-noising, artifact handling).

Extract features (time-domain / frequency-domain / bandpower / spectral features).

Reduce dimensionality (PCA / visualization).

Train & evaluate classifiers to separate scent-related neural signatures.

Save models & plots under Models/ and analysis_plots/.
