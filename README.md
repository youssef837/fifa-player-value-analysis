# ⚽ FIFA Player Market Value — ML Analysis

> Predicting FIFA player market value using **Principal Component Analysis (PCA)** and **Multiple Linear Regression** on 18,000+ players.

---

## 📌 Objective

Identify the key factors that influence a football player's market value (in million euros) using statistical and machine learning methods applied to the FIFA dataset.

---

## 🔍 Methods & Pipeline

| Step | Method |
|------|--------|
| Data Cleaning | Missing value removal, column renaming |
| Outlier Detection | IQR method (interquartile range) |
| Descriptive Stats | Mean, median, variance, quartiles |
| Visualization | Histograms, boxplots, bar charts |
| Dimensionality Reduction | Principal Component Analysis (PCA) |
| PCA Diagnostics | Scree plot, biplot, cos², variable contributions |
| Predictive Model | Multiple Linear Regression (MLR) |
| Model Validation | Train/Test split 80/20 — MAE, RMSE |
| Assumptions Check | VIF (multicollinearity), Shapiro-Wilk, QQ-plot |
| Prediction | Market value estimation with 95% confidence interval |

---

## 📊 Key Results

- **Target variable**: `Value_Euro_M` — player market value in million euros
- **Key predictors**: `Overall_Rating`, `Potential`, `Age`
- **PCA**: First 2 components explain the majority of variance
- **Metrics on test set**: MAE and RMSE reported in the notebook

---

## 🛠️ Tech Stack

- **Language**: R
- **Packages**: `factoextra`, `ggplot2`, `dplyr`, `readxl`, `car`, `caret`, `pROC`
- **Report format**: R Markdown (`.Rmd`) → PDF / Word

---

## 📁 Project Structure

```
fifa-player-value-analysis/
├── projet_fifa.Rmd        # Full analysis notebook (code + text + results)
├── data/
│   └── fifa.xlsx          # Raw dataset (18,000+ FIFA players)
└── README.md
```

---

## ▶️ How to Run

1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/fifa-player-value-analysis.git
```

2. Open `projet_fifa.Rmd` in **RStudio**

3. Install required packages
```r
install.packages(c("factoextra", "car", "ggplot2", "dplyr", "readxl"))
```

4. Click **Knit** to generate the full report (PDF or Word)

---

## 👥 Authors

- Abdellah Ben Hayoun
- Youssef Doumari
- Saad Belkhoumani
- Yahya Jada

---

## 📅 Date

May 2026

