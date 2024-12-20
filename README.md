# Face_recognition_using_SVC_PCA_sklearn

**Face Recognition using SVC, PCA, and Scikit-learn Pipeline**
This project implements a face recognition system using machine learning techniques. We leverage Principal Component Analysis (PCA) for dimensionality reduction and Support Vector Classification (SVC) for classification. The project is built with Python and Scikit-learn, utilizing pipelines to streamline the workflow.

**Introduction**
Face recognition is a widely-used application in security, biometrics, and social media. This project explores a machine learning approach to face recognition by combining PCA for feature extraction and SVC for classification. Scikit-learn's pipeline feature is used to ensure a modular, maintainable, and efficient implementation.

**Features**
Dimensionality Reduction: PCA is applied to extract the most important features from high-dimensional face data.
Classification: SVC is trained on the PCA-transformed features to distinguish between different faces.
Pipeline Implementation: The entire workflow (preprocessing, PCA, SVC) is encapsulated in a Scikit-learn pipeline.
Modular and Extensible: The project can be easily extended with additional preprocessing steps or alternative classifiers.

Libraries Used
Scikit-learn : For implementing PCA, SVC, and pipeline creation
Seaborn : For enhanced visualizations and heatmaps (e.g., confusion matrix).
Matplotlib : For visualizing data and model performance.

**Dataset**
The project requires a labeled dataset of facial images. You can use the Labeled Faces in the Wild (LFW) dataset or any other dataset of your choice. Ensure the dataset is properly preprocessed (e.g., resized, grayscale).

**Installation**
Clone the repository : git clone https://github.com/your_username/Face_recognition_using_SVC_PCA_sklearn.git
Install dependencies : pip install -r requirements.txt
Go to Google Colab & Create a new notebook.

**Pipeline Architecture**
The workflow is implemented as a Scikit-learn pipeline for better modularity and readability:

Preprocessing: Normalization and data splitting.
Feature Extraction: PCA to reduce dimensionality while retaining significant features.
Classification: SVC to classify faces based on the extracted features.

[Preprocessing] -> [PCA] -> [SVC]

**Results**
Accuracy: Achieved accuracy 0.85 and a precision of 0.86  on the test set.
Performance Metrics: Include precision, recall, F1-score, and confusion matrix.

**Potential Applications**
 Access Control and Security Systems
 Attendance Management System
 Criminal Identification in Law Enforcement

**Contributing**
Contributions are welcome!
Fork the repository.
Create a new branch : git checkout -b feature-name
Commit your changes : git commit -m "Add new feature"
Push to the branch : git push origin feature-name
Submit a pull request.
