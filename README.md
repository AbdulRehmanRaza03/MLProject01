# Stress Level Prediction using Machine Learning

## 📌 Project Overview
This project applies **Machine Learning techniques** to predict students' stress levels (Low, Medium, High) using psychological, academic, social, and environmental factors.  
The dataset contains **1,100 rows** and **21 features**, collected from a nationwide student survey.  

The goal of this project is to demonstrate how data-driven models can provide valuable insights into **mental health** and **academic performance**, enabling better support systems for students.

---

## 📂 Dataset
- **File**: `stressLevelDataset.csv`  
- **Rows**: 1,100  
- **Columns**: 21 (features)  
- **Target**: `stress_level` (3 classes: Low, Medium, High)  
- **Missing Values**: None  
- **Duplicates**: None  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Verified dataset integrity (no missing/duplicate values)  
- Converted categorical features into numeric (if applicable)  
- Standardized numerical features using `StandardScaler`  
- Target column encoded into 3 classes  

### 2. Exploratory Data Analysis (EDA)
- Histograms, bar plots, and scatter plots for feature distribution  
- Correlation heatmap to identify relationships between features  
- Insights: *Academic performance, study load, and anxiety levels strongly correlate with stress*  

### 3. Model Development
- Algorithm: **Support Vector Machine (SVM)**  
- Train-Test Split: 80% training, 20% testing  
- Scaling applied to ensure balanced feature ranges  

### 4. Results
- **Accuracy**: 85%  
- **Evaluation Metrics**: Confusion Matrix, Classification Report  
- Key Insight: *Study load, anxiety, and academic performance are primary indicators of stress.*  

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**:  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  
  - Model Persistence: `pickle`  

---

## 📊 Visuals
Include these plots for better understanding:  
- Feature distribution histograms  
- Stress level class distribution  
- Correlation heatmap  
- Scatter plot (e.g., anxiety_level vs stress_level)  
- Confusion matrix  

