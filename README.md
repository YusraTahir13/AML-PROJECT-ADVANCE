# Applied Machine Learning Project - ADVANCE

# Comparative Analysis of Machine Learning Algorithms for Alzheimer’s Disease Prediction 

This project focuses on the classification and prediction of Alzheimer’s Disease using machine learning techniques. Four different models _
**Support Vector Machine (SVM), Random Forest, Logistic Regression, and XGBoost** _ were developed  and compared to identify the most effective approach for early diagnosis based on clinical, demographic, and lifestyle feature.

## Dataset Information

**Dataset: Alzheimer_dataset**

**Source : [Kaggle website](https://www.kaggle.com/datasets/oumaymabejaoui/dataset-alzheimer)**

## Description
- Total patients: 2,149
- Total features: 36 variables spanning multiple domains including demographic, lifestyle and clinical data.
- Target variable: Diagnosis (0 = Healthy, 1 = Alzheimer’s Disease)

## Challenges
- Contains missing values (NaN) in some features.
- The dataset is imbalanced, with 1,389 healthy cases and 760 Alzheimer’s cases.
- High dimensional feature space, Need for proper feature selection and scaling.

## Methodology

The entire workflow is documented in the below notebook using executable code cells, along with Markdown cells for detailed descriptions.

[AML_Models_comparison](https://github.com/YusraTahir13/AML-PROJECT-ADVANCE/blob/main/AML_Models_All.ipynb)

**1. Data Preprocessing and cleaning**
- Checked dataset structure and summary statistics
- Handled missing values
- Analyzed class distribution
- Performed exploratory visualizations

**2. Feature Engineering & Selection**
- Applied feature scaling
- Selected relevant features for model training
- Reduced noise and redundancy

**3. Data Splitting**
- Train-test split applied for unbiased evaluation

**4. Model Building**

The following machine learning models were implemented:

* Support Vector Machine (SVM)
  
* Random Forest (RF)
  
* Logistic Regression (LR)
  
* XGBoost Classifier (XGB)

**5. Hyperparameter and Threshold Tuning**

- Applied GridSearchCV
- Used k-fold Cross Validation for robust optimization
- Adjusted classification thresholds to improve performance

**6. Model Evaluation**

Each model was evaluated using:
- Accuracy, Precision, Recall, F1-score, Confusion Matrix and ROC-AUC Score

**7.Results**

After comparative analysis:

- Random Forest achieved the best overall performance with Accuracy: 95.3% and ROC-AUC: 0.94
- XGBoost showed competitive results with Accuracy: 95.1% and Highest ROC-AUC: 0.95
- SVM performance moderate with Accuracy: 88% and ROC-AUC: 0.91
- Logistic Regression perform lowest with : Accuracy: 80.2% and ROC-AUC: 0.88
- All generated output figures have been saved in the [figures folder]() for reference.

**Conclusion**

- **Random Forest & XGBoost** performed significantly better than individual models.
- Feature selection and preprocessing improved prediction accuracy.
- Hyperparameter and Threshold tuning, and cross validation helped in better classification balance.
- Logistic Regression showed limitations with complex patterns in data.

**Bioinformatics Relevance**

This project demonstrates the application of machine learning in bioinformatics and medical diagnostics, where computational models assist in clinical decision support, Risk prediction and early disease detection.

## Author

Yusra Tahir

Master's student - Bioinformatics - University of Bologna




