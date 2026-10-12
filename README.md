# ML-zomecamp-HW3
ML zomecamp HW3
# Machine Learning Zoomcamp 2026 - Homework 3

This repository contains my solution for **Homework 3: Machine Learning for Classification** as part of the [DataTalks.Club Machine Learning Zoomcamp 2026](https://github.com/DataTalksClub/machine-learning-zoomcamp).

---

## 📌 Project Overview
In this homework, we build a customer conversion / lead scoring classification model using **Logistic Regression**. The project covers the full end-to-end exploratory data analysis and model training pipeline.

### **Key Steps & Tasks Covered:**
1. **Data Preparation & Cleaning:**
   - Standardized column names and categorical string values to lowercase.
   - Handled missing values (filled categorical missing values with `'N/A'` and numerical ones with `0`).
   - Split the dataset into training (`60%`), validation (`20%`), and test (`20%`) sets (`random_state=1`).
2. **Exploratory Data Analysis (EDA):**
   - Analyzed target variable distributions and global conversion rates.
   - Computed risk ratios and difference metrics for categorical features (`lead_source`, `industry`, `employment_status`, `location`).
   - Evaluated **Mutual Information (MI)** scores for categorical variables against the target.
   - Calculated **Pearson correlation coefficients** for numerical features (`annual_income`, `number_of_courses_viewed`, `interaction_count`, `lead_score`).
3. **Model Training & Evaluation:**
   - Utilized `DictVectorizer` to convert dataset dictionaries into sparse matrices for machine learning models.
   - Trained a **Logistic Regression** model using Scikit-Learn.
   - Evaluated model performance on validation data using **Accuracy** metrics.
4. **Hyperparameter Tuning & Feature Analysis:**
   - Performed feature selection experiments to evaluate the impact of individual features.
   - Tuned regularization parameters (`C`) to optimize model performance.

---

## 🛠️ Files in this Repository
* `homework3.ipynb`: The complete Jupyter Notebook containing all code, analysis, and experiments.
* `course_lead_scoring_2026.csv`: The dataset used for the homework assignment.

---

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone [https://github.com/egasmaaeldaly-88/ML-zomecamp-HW3.git](https://github.com/egasmaaeldaly-88/ML-zomecamp-HW3.git)
