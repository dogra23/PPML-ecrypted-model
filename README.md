                                          Privacy-Preserving Machine Learning for Breast Cancer Diagnosis

This project implements a Privacy-Preserving Machine Learning (PPML) pipeline to predict breast cancer outcomes securely using Homomorphic Encryption (HE). The sensitive medical data is protected using encryption techniques while still allowing machine learning models to be trained and evaluated.

OVERVIEW

This notebook demonstrates:
1. Loading and preprocessing the Breast Cancer Wisconsin dataset
2. Applying Homomorphic Encryption (CKKS scheme via TenSEAL)
3. Training a Logistic Regression classifier on encrypted data
4. Preserving patient privacy while enabling accurate predictions

HOW IT WORKS

-Data Loading: The Breast Cancer dataset is loaded from a local file. Features are cleaned and preprocessed for classification.

-Homomorphic Encryption: The dataset is encrypted using the CKKS scheme from TenSEAL. This allows computations to be performed directly on encrypted data.

-Model Training: A Logistic Regression model is trained on the encrypted feature vectors. Only encrypted data is used during training to preserve privacy.

-Evaluation: Model predictions are decrypted and compared to original labels. Accuracy is calculated to validate model performance.
