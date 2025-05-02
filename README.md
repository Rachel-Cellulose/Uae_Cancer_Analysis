# Uae_Cancer_Analysis

This project analyzes cancer patient data from the UAE to uncover trends, support diagnosis, and improve treatment strategies using data science methods.

---

## Objectives

### Exploratory Data Analysis (EDA)
- Analyze **recovery rates over the years**
- Examine **recovery rate by cancer type**
- Investigate **impact of smoking status** on patient outcomes
- Identify **top 5 most common cancer types** and their recovery performance

### Predictive Modeling *(Planned/Next Phase)*
- Predict **cancer stage (I, II, III, IV)** based on:
  - Demographics (Age, Gender, Nationality, Ethnicity)
  - Lifestyle factors (Smoking Status)
  - Medical history (Comorbidities, Cancer type, Weight, Height)

### Clustering Analysis *(Planned/Next Phase)*
- Apply unsupervised learning to group patients into hidden subgroups for deeper profiling.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `EDA_Cancer_Patients_UAE.ipynb` | Jupyter notebook with full code: data cleaning, visualizations, and EDA |
| `Cleaned_Cancer_Data.xlsx` | Cleaned and preprocessed version of the dataset |
| `visualizations/` | Saved images from the EDA plots (optional folder) |
| `README.md` | Project overview and documentation |

---

## Tools & Libraries Used

- **Google Colab** (Jupyter environment)
- **Python** (3.9+)
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Visualizations
- **NumPy** – Numerical analysis
- **Scikit-learn** *(to be used for ML & clustering)*

---

## Step-by-Step Workflow

### 1. **Data Preprocessing**
- Replaced missing placeholders like `'N/A'`, `'#####'` with `NaN`
- Converted dates to datetime format
- Converted Age, Weight, Height to numeric
- Removed rows with critical missing fields
- Exported cleaned data to Excel

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed trends in recovery rates by year and cancer type
- Compared outcomes across smoking status
- Identified most frequent cancer types
- Visualized insights using bar plots, line charts, and count plots

---

## Sample Visualizations

- Recovery Trends Over Time  
- Recovery Rate by Cancer Type  
- Patient Outcomes by Smoking Status  
- Frequency of Top 5 Cancer Types  

---

## How to Use

1. Open the notebook in Google Colab or Jupyter
2. Upload your dataset or use the provided cleaned Excel file
3. Run each cell block step-by-step to reproduce the analysis


