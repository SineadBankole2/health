Diabetes Risk Classifier — Pima Indians (Jupyter Notebook/vscode)

This project builds an end-to-end machine learning pipeline in Python to predict diabetes risk from tabular clinical features. It uses scikit-learn with a scaled, class-balanced Logistic Regression and evaluates with Accuracy, Precision, Recall, F1, and ROC-AUC. Artifacts such as the trained model, metrics, and plots are saved for reuse and documentation.
Highlights 

scikit-learn pipeline on the Pima Indians Diabetes dataset

Preprocessing: cleaning zeros to missing, median imputation, standardisation

Class-balanced Logistic Regression (class_weight="balanced")

Evaluation: Accuracy, Precision, Recall, F1, ROC-AUC + ROC and Confusion Matrix plots

Artifacts saved: artifacts/model.joblib, metrics.json, roc_curve.png, confusion_matrix.png

Notebook prediction helper for quick testing (optional CLI can be added later)
