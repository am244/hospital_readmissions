# Prediction of hospital readmissions of diabetic patients

This repo contains the Applied AI coursework to predict hospital readmissions for diabetic patients using machine learning. A linear Support Vector Machine (SVM) was selected as a baseline, and compared to an SVM with a Radial Basis Function (RBF) kernel, a Random Forest, and XGBoost. The Random Forest achieved the best performance across two experiments. For the first experiment, the coursework tasked us with using a cross-validation pipeline and single held-out test set; for the second, a nested cross-validation pipeline was required.

The dataset used includes ten years (1999-2008) of clinical care records of patients diagnosed with diabetes, compiled from 130 US hospitals and integrated delivery networks. This is publicly available in the [UCI Machine Learning](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008) repository.
The code can be found in the Jupyter notebook (`.ipynb`). The report pdf file is also provided.
