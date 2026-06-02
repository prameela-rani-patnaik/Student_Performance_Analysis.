# 🎓 Student Performance Analysis

A machine learning project that predicts whether a student will **pass or fail** based on academic and behavioural performance factors.

---

## 📌 Project Overview

This project uses **Logistic Regression** to classify student outcomes (Pass/Fail) from a dataset of **10,000 students**. It covers the full ML pipeline — from data exploration and preprocessing to model training, evaluation, and visualization.

> 💡 **Key Learning:** During development, I discovered a case of **data leakage** — using `math_score` to predict `pass_fail` which was derived from it. Fixing this taught me that high accuracy doesn't always mean a good model.

---

## 📂 Dataset Features

| Feature | Description |
|---|---|
| `study_hours_per_day` | Daily study hours |
| `attendance_rate` | % of classes attended |
| `sleep_hours` | Average sleep per night |
| `assignment_completion_rate` | % of assignments completed |
| `participation_score` | Class participation score |
| `previous_gpa` | GPA from previous term |
| `math_score`, `reading_score` etc. | Subject-wise scores |
| `pass_fail` | Target variable (Pass/Fail) |

---

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Results

| Metric | Score |
|---|---|
| Accuracy | 99.9% (before fixing leakage) |
| Recall | 1.0 |
| Confusion Matrix | [[768, 2], [0, 2230]] |

| Metric | Score |
|---|---|
| Accuracy | 83.4% (After fixing leakage) |
|F1-Score: | 89.2% |
| Confusion Matrix |[[ 451  319] [ 177 2053]] |

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/prameela-rani-patnaik/Student_Performance_Analysis

# Install dependencies
pip install pandas numpy matplotlib scikit-learn

# Open the notebook
jupyter notebook M1.ipynb
```

---

## 📈 What I Learned

- Logistic Regression for binary classification
- Confusion Matrix, Accuracy & Recall & F1-Score
- Data preprocessing & feature scaling
- How to identify  **data leakage**
- Data visualization with Matplotlib

---

## 👩‍💻 Author

**K. Prameela Rani**
🔗 [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/prameela-rani-patnaik)
