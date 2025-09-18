# multi-label-svm
Experiments in multi-class and multi-label classification using SVMs, clustering, and active learning on benchmark datasets (Anuran Calls, Breast Cancer, Banknote Authentication).

## Overview
This project explores advanced methods in multi-class and multi-label classification using Support Vector Machines (SVMs), clustering algorithms, and active learning strategies. The experiments are conducted on three benchmark datasets:<br>
- Anuran Calls (MFCCs): a hierarchical multi-label dataset (family, genus, species) used to evaluate SVMs with Gaussian kernels, L1-penalization, and SMOTE balancing techniques.<br>
- Breast Cancer Wisconsin (Diagnostic): a binary classification dataset for comparing supervised, semi-supervised, and unsupervised approaches, including k-means and spectral clustering.<br>
- Banknote Authentication: a binary classification dataset used to study the difference between active learning and passive learning with SVMs through Monte Carlo simulations.<br>

This project aims to investigate classification and learning strategies across multiple settings using the following Python libraries: pandas, matplotlib, seaborn, numpy, scikit-learn, imbalanced-learn, scipy

## Goals and Objectives
1.	Evaluate multi-label problems using metrics such as exact match, Hamming score, precision, recall, and ROC/AUC.<br>
2.	Solve multi-class and multi-label classification tasks with SVMs, including Gaussian kernels, L1 regularization, and classifier chains.<br>
3.	Address class imbalance with techniques like SMOTE and assess their impact on performance.<br>
4.	Compare learning paradigms by contrasting supervised, semi-supervised (self-training), and unsupervised methods (k-means, spectral clustering).<br>
5.	Explore active learning vs. passive learning with SVMs to understand data efficiency in model training.<br>

## Methods
- Supervised: SVM (Gaussian, linear, L1-regularized, OVA) <br>
- Semi-supervised: Self-training with SVMs<br>
- Unsupervised: K-means, Spectral Clustering<br>
- Active learning: Pool-based with uncertainty sampling<br>
- Imbalanced data handling: SMOTE, balanced sampling<br>

## Results
The following evaluation metrics were used:
- Multi-label metrics: Exact Match, Hamming Score, Hamming Loss <br>
- Classification metrics: Accuracy, Precision, Recall, F1-score, ROC, AUC<br>
- Unsupervised metrics: Hamming distance, silhouette scores<br>
- Learning curves: Active vs passive learning error rates<br>