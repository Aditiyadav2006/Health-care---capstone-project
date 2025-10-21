# Healthcare Data Analysis and Prediction Capstone Project

---

## 💡 Project Overview

This capstone project focuses on applying data science and machine learning techniques to a **healthcare dataset** to derive actionable insights and build predictive models. The project analyzes various patient and administrative factors (like age, medical condition, admission type, billing amount, and test results) to understand the healthcare landscape.

The primary goals were to:
1.  **Conduct extensive Exploratory Data Analysis (EDA)** to understand data distributions, correlations, and patient demographics.
2.  **Clean and preprocess** raw healthcare data for modeling readiness.
3.  **Develop and evaluate Machine Learning Classification Models** to predict a critical outcome, likely related to **patient status, treatment success, or a binary outcome (e.g., test result)**.

## 📊 Analysis & Methodology

The project follows a rigorous data science workflow documented across two main Jupyter notebooks:

### 1. Exploratory Data Analysis (EDA) & Data Preprocessing (`Healthcare_EDA.ipynb`)
* **Data Inspection:** Initial checks for missing values, data types, and unique categorical values.
* **Descriptive Statistics:** Summarizing key numerical fields like **Age** and **Billing Amount**.
* **Distribution Analysis:** Visualizing the frequency of categories such as **Medical Condition**, **Gender**, **Blood Type**, and **Insurance Provider**.
* **Feature Engineering/Encoding:** Transforming categorical variables (e.g., using Label Encoding or One-Hot Encoding) and scaling numerical features to prepare the data for the machine learning phase.

### 2. Machine Learning Modeling & Evaluation (`Healthcare_Cp.ipynb`)
* **Model Implementation:** Training and tuning a suite of classification models on the processed dataset:
    * **Support Vector Machines (SVM)**
    * **Naive Bayes (NB)**
    * **Decision Trees (DT)**
    * **Random Forests (RF)**
* **Performance Evaluation:** Comparing the models using industry-standard metrics, including **Accuracy Score**, **F1-Score**, and **Classification Reports** to identify the most robust predictor.
* **Visualization of Results:** Generating **Confusion Matrices** and accuracy bar plots to clearly illustrate model performance.

## 📁 Repository Structure

| File Name | Description |
| :--- | :--- |
| `healthcare_dataset.csv` | The raw dataset containing detailed patient records and associated administrative information. |
| `Healthcare_EDA.ipynb` | Jupyter Notebook detailing the entire Exploratory Data Analysis, data cleaning, feature engineering, and visualization process. |
| `Healthcare_Cp.ipynb` | Jupyter Notebook containing the setup for the machine learning pipeline, model training, hyperparameter tuning, and final model evaluation. |

## 🛠️ Technologies & Libraries

This project was built using **Python** and relies on the following key libraries:

* **Data Manipulation**: `pandas`, `numpy`
* **Visualization**: `matplotlib`, `seaborn`
* **Machine Learning**: `scikit-learn` (for preprocessing, model selection, and metrics)
* **Environment**: `VS code `

You can also view the notebook directly on GitHub or platforms like **Google Colab** without needing a local setup.

***

## 👩‍💻 Author
**Aditi K**  
CSE (AI & ML) | Health care | Capstone project  
