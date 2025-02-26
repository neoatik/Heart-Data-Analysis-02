# Exploratory Data Analysis (EDA) of Heart Data

## Overview
This project involves performing an Exploratory Data Analysis (EDA) on heart disease-related data. The goal is to extract meaningful insights, visualize key trends, and preprocess the data for further analysis. Additionally, machine learning models were built in the final stage to predict heart disease risk.

## Dataset
The dataset contains various features related to heart health, such as age, cholesterol levels, blood pressure, smoking status, and heart attack risk indicators.

## Key Steps
### 1. Data Preprocessing
- Handled missing values
- Converted categorical variables into numerical format
- Scaled features using Min-Max Scaling
- Applied SMOTE Oversampling to balance the dataset

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Distribution of numerical and categorical features using histograms and count plots
- **Bivariate Analysis**: Relationship between independent variables and target using scatter plots, pair plots, and correlation heatmaps
- **Group-wise Analysis**: Heart attack risk based on age groups, smoking status, and other health factors

### 3. Visualizations
- Count plots for categorical variables
- Histograms for numerical distributions
- Heatmap to analyze feature correlations
- Box plots to detect outliers
- Pair plots to visualize relationships between variables

### 4. Feature Engineering
- Created new features based on domain knowledge
- One-hot encoding for categorical variables
- Feature selection based on importance scores

### 5. Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Evaluated model performance using accuracy, precision, recall, and F1-score

## Results
- Identified key risk factors for heart disease
- Visualized trends in heart attack risk across age and lifestyle choices
- Built predictive models with good accuracy for heart disease classification

## Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/heart-data-eda.git
cd heart-data-eda
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook EDA_of_Heart_Data.ipynb
```



