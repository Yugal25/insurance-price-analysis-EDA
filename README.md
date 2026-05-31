# Insurance Charges Analysis

Exploratory data analysis and feature selection on the Medical Insurance dataset
to identify the most significant factors influencing insurance charges.

## Project Overview
This project explores the factors that influence medical insurance charges using
data analysis, feature engineering, and statistical testing techniques.
The goal is to identify which features have the strongest relationship with
insurance costs and prepare the dataset for future machine learning models.

## Project Workflow

### 1. Data Cleaning
* Checked for missing values
* Verified data types
* Prepared data for analysis

### 2. Exploratory Data Analysis (EDA)
* Distribution analysis using histograms
* Correlation analysis between numerical variables
* Visualization of feature relationships

### 3. Feature Engineering
* Created BMI categories:
  * Normal
  * Overweight
  * Obese
* Applied one-hot encoding to categorical variables
* Generated binary indicator variables

### 4. Feature Scaling
* Standardized numerical features using StandardScaler:
  * Age
  * BMI
  * Children

### 5. Statistical Analysis

#### Pearson Correlation Test
Used Pearson Correlation to measure relationships between numerical features
and insurance charges.

#### Chi-Square Test
Used Chi-Square testing to evaluate relationships between categorical variables
and categorized insurance charges.

## Key Findings
* Smoking status showed the strongest relationship with insurance charges.
* Age and BMI were positively associated with higher insurance costs.
* Certain BMI categories demonstrated significant relationships with insurance charges.
* Regional features showed relatively weaker relationships compared to smoking status and BMI.

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Jupyter Notebook

## Future Improvements
* Build Linear Regression models
* Compare multiple machine learning algorithms
* Perform feature importance analysis
* Evaluate model performance using R², MAE, and RMSE

## Author
Yugal Sapkota
This project was created as part of my machine learning and data science learning journey.
