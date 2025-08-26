# Framingham Heart Disease Prediction

## 📌 Project Overview
This project uses the **Framingham Heart Study dataset** to predict the **10-year risk of developing coronary heart disease (CHD)**.  
The notebook performs data cleaning, exploratory data analysis (EDA), and applies machine learning models to predict disease risk.

## 📂 Dataset
- **File:** `framingham.csv`  
- **Target Variable:** `TenYearCHD` (1 = CHD within 10 years, 0 = no CHD)  
- **Features include:** age, gender, education, smoking status, cholesterol levels, blood pressure, diabetes, BMI, heart rate, etc.  

### Data Preprocessing
- Checked and handled **missing values**  
- Converted categorical variables into numeric encodings  
- Normalized/standardized features where necessary  

## 🔎 Exploratory Data Analysis (EDA)
- Distribution of target variable (`TenYearCHD`)  
- Correlation analysis between features and target  
- Visualization of risk factors such as:
  - Age vs. CHD risk  
  - Cholesterol vs. CHD risk  
  - Smoking habits and CHD incidence  

## 🤖 Machine Learning
### Steps:
1. Define features (X) and target (y)  
2. Split dataset into training & test sets  
3. Train machine learning models  
4. Evaluate model performance  

### Models Used:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Other classifiers as tested  

## 📊 Results
- Accuracy, Precision, Recall, F1-score compared across models  
- Feature importance analysis for risk prediction  
- Best-performing model identified for CHD prediction  

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone <your-repo-link>
   cd framingham-heart
