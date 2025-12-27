# IBM-Hr-Analytic-Attribition

# HR Analytics – Employee Attrition Prediction

## 📌 Project Overview
This project analyzes employee attrition using HR data.  
We apply a full data science workflow: from data inspection and preprocessing to modeling and business interpretation.

Bu proje, çalışan kaybını (attrition) HR verisi üzerinden analiz eder.  
Veri bilimi sürecinin tüm adımları uygulanır: veri inceleme, ön işleme, modelleme ve iş değeri yorumlama.

---

## 🗂 Workflow Steps

### Step 1: Project Setup & Context
- Load dataset
- Define target variable (`Attrition`)

### Step 2: Data Inspection
- Check missing values
- Explore categorical/numeric features

### Step 3: Exploratory Data Analysis (EDA)
- Attrition distribution
- Age distribution
- OverTime effect
- Correlation heatmap

### Step 4: Preprocessing & Feature Engineering
- Encode categorical variables
- Scale numerical features
- Train/test split

### Step 5: Modeling
- Logistic Regression (baseline)
- Random Forest (ensemble)
- Support Vector Machine (SVM)
- Gradient Boosting (advanced)

### Step 6: Results Comparison
- Accuracy, Precision, Recall, F1-score
- Summary table

### Step 7: Interpretation & Business Value
- Identify best-performing model
- Highlight key drivers of attrition
- HR recommendations

### Step 8: Final Presentation
- Results summary
- Feature importance visualization
- Business recommendations

---

## 📊 Results
- **Best Model:** Random Forest / Gradient Boosting (depending on dataset split)
- **Key Features:** OverTime, JobSatisfaction, Age, MonthlyIncome
- **Business Value:** Helps HR identify employees at risk of leaving and take proactive actions.

---

## ⚙️ Tech Stack
- Python 3.x
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

---

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/yourusername/hr-attrition-prediction.git
cd hr-attrition-prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook HR_Attrition.ipynb
