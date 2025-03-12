Predictive Efficacy Discovery (PED) Model for Alzheimer's Drug Discovery

Project Overview

This project focuses on implementing a Predictor-Encoder-Decoder (PED) model to identify novel drug molecules that can potentially cure or alleviate the symptoms of Alzheimer's disease. The approach leverages machine learning techniques and computational drug discovery methodologies to predict the efficacy of new compounds.

Database Used: CHEMBL

The dataset used for training and validation is derived from the ChEMBL database, a comprehensive bioactivity database that contains information on molecules currently used in the treatment of Alzheimer's disease. The database provides details on drug-target interactions, bioactivity measurements, and molecular properties essential for drug discovery.

Methodology

Data Collection & Preprocessing

Extracted molecules related to Alzheimer's treatment from the CHEMBL database.

Processed molecular structures into SMILES representation.

Feature Engineering & Model Training

Employed feature extraction methods like molecular descriptors and fingerprints.

Used Deep Learning models to predict drug efficacy.

Applied validation techniques such as cross-validation and external test set evaluation.

Prediction & Candidate Selection

Evaluated new molecules based on predicted bioactivity scores.

Identified potential drug candidates for further experimental validation.

Dependencies

Python (pandas, scikit-learn, RDKit, TensorFlow/PyTorch)

CHEMBL API for dataset extraction

Jupyter Notebook for model development

Contributors

Sarthak Toshniwal

Acknowledgments

Special thanks to the CHEMBL database for providing extensive molecular data and resources for computational drug discovery.

