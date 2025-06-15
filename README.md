# BREAST-CANCER-THROUGH-EDA
BREAST CANCER PROJECT THROUGH VISUALS
-------- 🎯PERFORMED BY ANURAG
# Breast Cancer Wisconsin (Diagnostic) Dataset - EDA & ML Pipeline

This project performs full data analysis and modeling on the Breast Cancer Wisconsin (Diagnostic) dataset using Python. The goal is to classify tumors as malignant (M) or benign (B) based on features computed from digitized images of fine needle aspirates (FNA) of breast masses.

## Dataset

- Original Source: UCI Machine Learning Repository
- Features: 32 numeric features (mean, worst, and standard error of cell nuclei measurements)
- Target: `Diagnosis` (M = Malignant, B = Benign)

## Project Workflow

1. **Data Loading**
    - Read the dataset from provided CSV or text file.
2. **Preprocessing**
    - Dropped `ID` column (non-informative unique identifier).
    - Encoded `Diagnosis` column (`M` → 1, `B` → 0).
3. **Exploratory Data Analysis (EDA)**
    - Countplot for class distribution.
    - Scatter plots for feature relationships.
    - Boxplots for outlier detection.
    - Correlation heatmap for feature inter-relationships.
4. **Feature Scaling**
    - Applied normalization or standardization for ML models.
5. **Model Building**
    - Classification models (e.g., Logistic Regression, Random Forest, etc.).
6. **Model Evaluation**
    - Accuracy, Confusion Matrix, Precision, Recall, F1-Score.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## How to Run

1. Clone the repository:
    ```bash
    git clone <your-repo-link>
    cd <your-repo-directory>
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook or Python scripts:
    ```bash
    jupyter notebook
    ```

## Visualization Samples

- Countplot of Diagnosis
- Scatterplot (Radius Mean vs Area Mean)
- Correlation Heatmap
- Boxplots for feature distributions

## Project Structure

```bash
├── data/
│ └── breast_cancer_wisconsin_diagnostic.csv
├── notebooks/
│ └── eda_and_modeling.ipynb
├── README.md
└── requirements.txt
