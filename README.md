# Recipe Site Traffic Analysis Project

## Overview
This project analyzes recipe site traffic to understand the factors influencing recipe popularity and develop predictive models for high-traffic recipes.

---

## Project Objectives
- Validate and clean recipe site traffic dataset  
- Perform exploratory data analysis (EDA)  
- Develop machine learning models to predict recipe traffic  
- Identify key factors contributing to recipe popularity  

---

## Dataset Description

### Columns
- **Recipe ID**  
- **Calories**  
- **Carbohydrates**  
- **Sugar**  
- **Protein**  
- **Category**  
- **Servings**  
- **High-traffic status**  

### Dataset Statistics
- **Total Rows:** 947  
- **Missing Values:** Handled during preprocessing  
- **Categories:** 10 unique recipe categories  

---

## Data Preprocessing

### Key Cleaning Steps
1. **Handle missing values:**  
   - Numerical columns: Replaced with median  
   - High-traffic column: Replaced with "Low"  
2. **Data type transformations**  
3. **Category consolidation**  
4. **Duplicate row removal**  

---

## Exploratory Data Analysis (EDA)

### Key Insights
#### Most Popular Recipe Categories:
- Vegetables  
- Potato  
- Pork  

### Visualization Techniques
- Pair plots  
- Count plots  
- Bar plots  
- Box plots  
- Violin plots  
- Kernel Density Estimation (KDE) plots  

### Statistical Analysis
- **T-tests conducted** to compare nutritional variables  
- Significant differences found in:  
  - Calories  
  - Carbohydrates  
  - Sugar content  

---

## Machine Learning Models

### Problem Type
**Binary Classification** (High/Low Traffic Prediction)  

### Models Developed
- Logistic Regression  
- Random Forest Classifier  

### Model Performance
- **Accuracy:** Approximately 76%  
- **Evaluation Metrics:**  
  - Precision  
  - Recall  
  - F1-score  

---

## Key Findings

### Recipe Category Importance
- Category plays a crucial role in recipe popularity  
- Vegetables, potato, and pork recipes are most requested  

### Nutritional Variables
- Slight correlation between nutritional content and traffic  
- Higher calories, protein, and carbohydrates tend to indicate high traffic  
- Sugar content shows an inverse relationship  

### Servings
- No significant impact on recipe traffic  

---

## Libraries Used
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `scipy`  

---

## Recommendations
1. Focus on promoting vegetable, potato, and pork recipes  
2. Consider nutritional content when developing new recipes  
3. Use predictive models to optimize recipe recommendations  

---

## Future Work
- Develop more advanced machine learning models  
- Collect additional features  
- Create a real-time recommendation system  

---

## How to Reproduce

1. **Clone the repository**  
2. **Install required dependencies**  
3. **Run data preprocessing script**  
4. **Execute EDA notebook**  
5. **Train and evaluate machine learning models**  

---

## Contributors
- **Data Scientist:** Meryem Mosref




![daaaaa](https://github.com/user-attachments/assets/8f009035-e70f-4d5d-9132-0d20f4b85160)

