# Student_Depression_Classification
Class project. Classifying students as potentially depressed in order to get them care. Supervised ML.


This project uses Python, pandas, and scikit-learn to classify student depression labels from demographic, academic, and lifestyle data, comparing K-Nearest Neighbors and Gaussian Naive Bayes models. The workflow combines numerical standardization, categorical encoding, and model training within preprocessing pipelines, with five-fold stratified cross-validation and a held-out test set for evaluation. Gaussian Naive Bayes achieved 97.9% test accuracy, 92.5% recall, and a mean cross-validation ROC-AUC of 0.987, with Matplotlib visualizations comparing model performance.
