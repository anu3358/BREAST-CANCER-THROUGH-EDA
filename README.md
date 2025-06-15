# BREAST-CANCER-THROUGH-EDA
BREAST CANCER PROJECT THROUGH VISUALS
Breast Cancer Wisconsin (Diagnostic) Dataset - EDA & ML Pipeline
This project performs full data analysis and modeling on the Breast Cancer Wisconsin (Diagnostic) dataset using Python. The goal is to classify tumors as malignant (M) or benign (B) based on features computed from digitized images of fine needle aspirates (FNA) of breast masses.

Dataset
Original Source: UCI Machine Learning Repository
Features: 32 numeric features (mean, worst, and standard error of cell nuclei measurements)
Target: Diagnosis (M = Malignant, B = Benign)
Project Workflow
Data Loading
Read the dataset from provided CSV or text file.
Preprocessing
Dropped ID column (non-informative unique identifier).
Encoded Diagnosis column (M → 1, B → 0).
Exploratory Data Analysis (EDA)
Countplot for class distribution.
Scatter plots for feature relationships.
Boxplots for outlier detection.
Correlation heatmap for feature inter-relationships.
Feature Scaling
Applied normalization or standardization for ML models.
Model Building
Classification models (e.g., Logistic Regression, Random Forest, etc.).
Model Evaluation
Accuracy, Confusion Matrix, Precision, Recall, F1-Score.
Tools & Libraries
Python
Pandas
NumPy
Seaborn
Matplotlib
Scikit-learn
How to Run
Clone the repository:

git clone <your-repo-link>
cd <your-repo-directory>
Install dependencies:

pip install -r requirements.txt
Run the notebook or Python scripts:

jupyter notebook
Visualization Samples
Countplot of Diagnosis
Scatterplot (Radius Mean vs Area Mean)
Correlation Heatmap
Boxplots for feature distributions
Project Structure
├── data/
│   └── breast_cancer_wisconsin_diagnostic.csv
├── notebooks/
│   └── eda_and_modeling.ipynb
├── README.md
└── requirements.txt
