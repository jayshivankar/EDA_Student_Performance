# 📊 Exploratory Data Analysis on Student Habits & Academic Performance

## Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) on a dataset that captures the relationship between students' habits and their academic performance. The goal is to extract actionable insights that can help educators, academic advisors, and policy makers better understand factors affecting student success.

---

## 📁 Dataset

The dataset (`student_habits_performance.csv`) includes anonymized information about students, including:

- 🎓 Academic performance (e.g., grades)
- 🕒 Study hours per day
- 😴 Sleep duration
- 🌐 Internet usage
- 🏃 Participation in extracurricular activities
- 🧬 Demographics (age, gender, etc.)

---

## 🛠️ Tools & Libraries

The following Python libraries were used for data analysis and visualization:

- `pandas` – data manipulation
- `numpy` – numerical operations
- `matplotlib` / `seaborn` – static visualizations
- `plotly` – interactive visualizations
- `scipy` – statistical testing

---

## 📌 Steps in the EDA

### 1. Data Cleaning
- Handled missing values
- Removed or imputed outliers
- Converted data types
- Encoded categorical variables

### 2. Univariate Analysis
- Histograms, bar plots, and box plots
- Summary statistics

### 3. Bivariate Analysis
- Correlation heatmaps
- Boxplots of habits vs performance
- Grouped comparisons

### 4. Multivariate Analysis
- Pair plots to explore clusters
- Cross-feature summaries using pivot tables
- PCA or clustering (optional advanced section)

### 5. Statistical Analysis
- Correlation coefficients (Pearson/Spearman)
- T-tests and ANOVA for group comparison

---

## 🔍 Key Insights

- 📈 Students with 2–4 hours of daily study tend to perform better academically.
- 🌙 Sleep between 6–8 hours is associated with higher performance.
- 📉 Excessive internet usage negatively correlates with grades.
- 🤹 Balanced involvement in extracurriculars shows modest academic benefit.

---

## 📈 Visuals

Visualizations are located in the `visuals/` directory and include:

- Correlation Heatmap
- Performance by Study Hours
- Internet Usage vs. Grades
- Sleep Patterns vs. Grades
- Interactive Dashboards (Plotly)

---

## 📂 Project Structure

```
student-eda-performance/
├── data/
│   └── student_habits_performance.csv
├── notebooks/
│   └── EDA_student_habits.ipynb
├── visuals/
│   └── *.png / *.html charts
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/student-eda-performance.git
cd student-eda-performance
pip install -r requirements.txt
jupyter notebook notebooks/EDA_student_habits.ipynb
```

---

## ✅ Future Enhancements

- Predictive modeling using insights (e.g., regression, classification)
- Feature engineering for more robust predictors
- Dashboard deployment using `Streamlit` or `Dash`

