#  Predicting Household Annual Income Using Demographic Data

## Project Overview
This project builds a supervised machine learning model to predict household annual income levels using demographic attributes. It demonstrates the full data science workflow: data ingestion, cleaning, missing value handling, recoding, EDA, feature engineering, and training classification models.

The dataset contains **8993 rows** and **14 demographic attributes**, with the goal of predicting income category (9 classes).  
Missing values are encoded as `NA`.

---

## 📁 Dataset Description
The demographic variables include:  
- Gender  
- Marital status  
- Age group  
- Education level  
- Occupation  
- Household size  
- Household children under 18  
- Housing type  
- Ethnicity  
- Primary home language  
- Duration living in the Bay Area  
- Dual income status  

The target variable is:

**Annual Income of Household**  
Categorized into 9 income brackets, ranging from *less than \$10,000* to *\$75,000 or more*.  
Source info from the dataset: :contentReference[oaicite:1]{index=1}

---

## Key Data Cleaning Steps
- Removing rows with missing target values  
- Handling missing demographic values  
- Encoding categorical variables (label encoding + one-hot)  
- Removing outliers where applicable  
- Transforming household counts into numeric forms  
- Verifying class balance  

---

## Exploratory Data Analysis
Conducted analysis on:
- Income distribution  
- Education vs income  
- Occupation vs income  
- Housing status vs income  
- Language vs income  
- Ethnicity vs income  

Visualization tools:  
`pandas`, `matplotlib`, `seaborn`

---

## Machine Learning Models
Trained classification models to predict income levels:
- Decision Tree Classifier  
- K-Nearest Neighbors  
- Logistic Regression (multiclass)  
- Baseline accuracy comparison  

Evaluated using:
- Accuracy  
- Confusion Matrix  
- Precision/Recall per income class

---

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## Repository Structure
project/
│
├── notebooks/
│ └── Assignment2.ipynb
│
├── data/
│ ├── income_data.csv
│ ├── income_big.csv
│ └── income_info.txt
│
├── reports/
│ └── (optional) Assignment2.pdf
│
└── README.md

---

## Key Outcomes
- Demonstrated ability to work with real demographic survey data  
- Handled missing data and high-cardinality categorical variables  
- Built and evaluated multiclass classification models  
- Delivered a clean, organized, portfolio-ready machine learning project  

---

### Author
**Adanma Okoroafor**  
MS Artificial Intelligence & Business Analytics (FinTech)  
University of South Florida  

