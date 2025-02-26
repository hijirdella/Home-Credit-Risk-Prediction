# Home Credit Default Risk Prediction: Data Science Final Project

<p align='center'>
  <a href="#"><img src="https://github.com/hijirdella/home-credit-risk-prediction/blob/5cc29ace011ea61df28b797b0ca40a2cb4771a73/Award/Home%20Credit%20GIF.gif" width="400"></a>
</p>

<p align='center'>
  <img src="https://github.com/hijirdella/home-credit-risk-prediction/blob/5cc29ace011ea61df28b797b0ca40a2cb4771a73/Award/Certificate%20of%20Awardee%20-%20Hijir%20Della%20Wirasti%20-%20The%20Best%20Group%20of%20Final%20Project%20(Byte%20Me)_page-0001.jpg" width="350">
  <img src="https://github.com/hijirdella/home-credit-risk-prediction/blob/5cc29ace011ea61df28b797b0ca40a2cb4771a73/Award/Certificate%20of%20Awardee%20-%20Hijir%20Della%20Wirasti%20-%20The%20Best%20Student%20of%20Final%20Project%20(Byte%20Me)_page-0001.jpg" width="350">
</p>

---

# Home Credit Default Risk Prediction: Data Science Final Project

<p align='center'>
  <a href="#"><img src="https://github.com/hijirdella/home-credit-risk-prediction/blob/5cc29ace011ea61df28b797b0ca40a2cb4771a73/Award/Home%20Credit%20GIF.gif" width="400"></a>
</p>

<p align='center'>
  <img src="https://github.com/hijirdella/home-credit-risk-prediction/blob/5cc29ace011ea61df28b797b0ca40a2cb4771a73/Award/Certificate%20of%20Awardee%20-%20Hijir%20Della%20Wirasti%20-%20The%20Best%20Group%20of%20Final%20Project%20(Byte%20Me)_page-0001.jpg" width="350">
  <img src="https://github.com/hijirdella/home-credit-risk-prediction/blob/5cc29ace011ea61df28b797b0ca40a2cb4771a73/Award/Certificate%20of%20Awardee%20-%20Hijir%20Della%20Wirasti%20-%20The%20Best%20Student%20of%20Final%20Project%20(Byte%20Me)_page-0001.jpg" width="350">
</p>

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Workflow Stages](#workflow-stages)
   - [Stage 0: Preparation](#stage-0-preparation)
   - [Stage 1: Exploratory Data Analysis (EDA)](#stage-1-exploratory-data-analysis-eda)
   - [Stage 2: Preprocessing](#stage-2-preprocessing)
   - [Stage 3: Machine Learning](#stage-3-machine-learning)
   - [Stage 4: Final Presentation](#stage-4-final-presentation)
3. [Key Insights and Results](#key-insights-and-results)
4. [Business Recommendations](#business-recommendations)
5. [Model Performance](#model-performance)
6. [How to Use](#how-to-use)

---

## Project Overview

The **Data Science Final Project** focuses on predicting the risk of customer default using historical loan application data. By leveraging robust data preprocessing, feature engineering, and advanced machine learning techniques, this project aims to provide actionable insights to improve credit risk management for Home Credit.

---

## Workflow Stages

### Stage 0: Preparation
- **Tasks**: Data collection, initial data inspection, and understanding business requirements.
- **Deliverables**: Raw datasets and project goals.

### Stage 1: Exploratory Data Analysis (EDA)
- **Techniques**:
  - Statistical analysis of key variables.
  - Visualizations to identify patterns and correlations.
- **Objective**: Identify trends and potential predictors for default risk.

### Stage 2: Preprocessing
- **Steps**:
  1. **Data Cleansing**: Handling missing values, removing duplicates, and transforming features.
  2. **Feature Engineering**: Adding new features such as credit ratios and tenure groups.
  3. **Encoding**: Binary and one-hot encoding for categorical variables.
  4. **Handling Class Imbalance**: Using oversampling (SMOTE) and undersampling techniques.
  5. **Normalization**: Standardizing numerical features to improve model performance.

### Stage 3: Machine Learning
- **Models Used**:
  - **AdaBoost**: Combines weak classifiers into a strong classifier adaptively, achieving high accuracy without requiring complex models.
  - **Decision Tree**: A flexible algorithm for classification and regression, capable of handling numeric and categorical data while generating intuitive tree structures.
  - **Random Forest**: An ensemble of decision trees trained on random data subsets, suitable for classification and regression tasks.
  - **KNN (K-Nearest Neighbors)**: A lazy learning algorithm that classifies data points based on their neighbors, effective for handling local data patterns.
  - **XGBoost**: Known for its high speed and efficiency, XGBoost excels at processing sparse data and controlling overfitting through regularization.
  - **Stacking**: Combines predictions from multiple base models through meta-modeling to enhance prediction accuracy.
  - **Logistic Regression**: A proven method for predicting loan defaults, with a focus on interest rates as a key predictor.

- **Evaluation Metrics**:
  - ROC-AUC, Recall, Precision, F1-Score, and F2-Score.
- **Tuning**: Hyperparameter optimization for improved model performance.

### Stage 4: Final Presentation
- **Deliverables**:
  - Summary of model results and business insights.
  - Recommendations for improving credit policy and reducing default rates.

---

## Key Insights and Results

- The XGBoost model provided the best balance between recall and precision, making it suitable for identifying high-risk customers.
- The optimized model successfully reduced the predicted default rate from **8.04%** to **0.96%**, aligning with Home Credit's business goals.

---

## Business Recommendations

1. **Focus on Customer Segmentation and Retargeting**:
   - Target high-risk sectors like Consumer Electronics and Connectivity with specialized credit offers.
2. **Enhance Default Prediction Accuracy**:
   - Use demographic and behavioral features for better risk profiling.
3. **Flexible Credit Policies**:
   - Offer competitive interest rates for low-risk customers and incentivize loyalty.

---

## Model Performance

Below are the key evaluation metrics for the best-performing model, **XGBoost**, before and after hyperparameter tuning:

| Metric | XGBoost Before Tuning | XGBoost After Tuning |
|--------|----------------------|----------------------|
| ROC AUC (Train Set) | 0.9646 | 0.9861 |
| ROC AUC (Test Set) | 0.9469 | 0.9470 |
| Accuracy (Train Set) | 0.9466 | 0.9397 |
| Accuracy (Test Set) | 0.9387 | 0.9397 |
| F2-Score (Test Set) | 0.8483 | 0.8519 |
| Recall (Cross-Validation Train) | 0.8197 | 0.8239 |
| Recall (Test Set) | 0.8176 | 0.8220 |
| Recall (Cross-Validation Test) | 0.8165 | 0.8208 |

These results indicate that hyperparameter tuning significantly improved the recall and AUC scores, enhancing the model's ability to correctly identify high-risk borrowers.

---

## How to Use

To reproduce this project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/hijirdella/home-credit-risk-prediction.git
   ```
2. Navigate to the project directory:
   ```sh
   cd home-credit-risk-prediction
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the model training script:
   ```sh
   python train_model.py
   ```
5. View results and insights in the output folder.

---

