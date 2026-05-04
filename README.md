# GenderPayGap Analysis
## 📊 Overview
This project investigates the **gender wage gap** using U.S. Current Population Survey (CPS) 1981-2013 data. It analyzes how demographic, educational, and occupational factors influence income, and examines how these effects differ between men and women.

The project combines **statistical modeling and machine learning** to both:
- identify key drivers of income  
- understand how wage determinants vary across groups  

---

## 🧠 Methods

### 1. Data Cleaning & Preprocessing
- Removed irrelevant and redundant variables  
- Handled missing values  
- Converted categorical variables into factors  
- Filtered dataset for analysis  

---

### 2. Feature Selection (LASSO)
- Applied **LASSO regression (glmnet)**  
- Used cross-validation to select optimal regularization parameter  
- Identified key predictors of income from a high-dimensional dataset  

---

### 3. Statistical Modeling
- Built **multiple linear regression models**  
- Performed **ANOVA tests** for significance  
- Included **interaction terms** such as:
  - gender × age  
  - gender × work experience  
  - gender × race  
  - gender × education  

---

### 4. Visualization
- Created plots to visualize:
  - salary vs. gender  
  - salary vs. education  
  - salary vs. experience  
- Used interaction plots to show how income changes across groups  

---

### 5. Machine Learning Models
- Implemented:
  - **Decision Trees**
  - **Random Forest**
- Tuned parameters (e.g., `mtry`)  
- Evaluated performance using **Mean Squared Error (MSE)**  

---

## 📊 Presentation

See the full project summary, visualizations, and results in the Pay Gap Slides.pdf

---

## 👥 Authors

- Xinying Chen  
- Cynthia Deng  
- Zhiyuan Ma  
- Tiffany Wei  
- Huey Yi  
- Sultan Al Dhaheri  

Supervised by: Neil Fasching  

