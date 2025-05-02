# UAE Cancer Patient Data Analysis Using Machine Learning

## 📌 Objective  
To develop a machine learning solution that analyzes cancer patient data from the UAE in order to:
- Classify patient stages of cancer based on demographic, lifestyle, and medical history
- Identify hidden patient clusters for more personalized treatment
- Support early diagnosis and reveal actionable insights

## 🔍 Research Goals

### I. Exploratory Data Analysis (EDA)
- Analyzed recovery rates across years
- Investigated recovery rate by cancer type
- Evaluated the impact of smoking status on outcomes
- Identified top 5 most common cancer types and compared recovery patterns

### II. Predictive Modeling

**Target Variable:** Cancer stage (I, II, III, IV)

**Features Used:**
- Demographics: Age, Gender, Nationality, Ethnicity  
- Lifestyle: Smoking Status  
- Medical history: Cancer Type, Weight, Height

**Approach:**
- Baseline model using Random Forest
- Improved with XGBoost
- Applied SMOTE to handle class imbalance
- Evaluated using accuracy, confusion matrix, and classification report

**Model Performance:**

| Model           | Accuracy | Stage IV Recall | Notes                             |
|----------------|----------|-----------------|------------------------------------|
| Random Forest   | 32%      | 7%              | Best overall balance               |
| XGBoost         | 28%      | 6%              | Underperformed on Stage IV         |
| XGBoost + SMOTE | 26%      | 8%              | Slight Stage IV improvement        |

### III. Clustering Analysis

**Goal:** Group patients into similar subgroups using unsupervised learning (without using the cancer stage)

**Method:**  
- KMeans Clustering (4 clusters)
- PCA for 2D visualization

**Features Used:**
Age, Gender, Nationality, Ethnicity, Smoking Status, Cancer Type, Weight, Height

**Cluster Insights:**

| Cluster | Key Traits |
|---------|------------|
| 0 | Mostly male, non-smokers |
| 1 | Majority female, highest smoking rate |
| 2 | Mixed gender, mostly foreign nationals |
| 3 | Entirely female, all local nationality |

## 🧰 Tools & Libraries Used
- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- PCA

## 📁 Deliverables
- `cancer_modeling.ipynb`: modeling and evaluation
- `EDA0.ipynb`: exploratory data analysis
- Cluster visualizations
- Final GitHub repo with version control

## 🖼️ Next Steps
- Finalize 10-slide presentation
- Include visual summaries (EDA, model, clusters)
- Submit project and prep for team presentation
