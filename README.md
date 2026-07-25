<h1 align="center">🧾 Model Card: hiren-keraliya-v1</h1>
<p align="center"><sub>a human, fine-tuned on curiosity and messy datasets</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-actively--training-1f8a4c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/license-open--to--work-2f6fed?style=for-the-badge" />
  <img src="https://img.shields.io/badge/base-BCA%20Graduate-8a3fc9?style=for-the-badge" />
</p>

---

### 📋 Model Details

| Field | Value |
|---|---|
| **Name** | Hiren Keraliya |
| **Version** | Post-internship, certified |
| **Type** | Data Scientist (with a web dev side-quest) |
| **Base education** | BCA — Silver Oak University, Ahmedabad |
| **Fine-tuned by** | Rubixe — 6-month Data Science Consultant Internship |
| **Architecture** | Python → pandas → scikit-learn → decisions |
| **Location** | Ahmedabad, India |

---

### 🎯 Intended Use

**Primary use cases:**
- Turning inconsistent, incomplete, real-world data into models that hold up outside the notebook
- Explaining *why* a model failed, not just that it did
- Full-stack builds when a project needs a front end wrapped around the analysis

**Not optimized for:** perfectly clean, pre-labeled Kaggle datasets with no missing values — those are for warm-ups, not the main event.

---

### 🧪 Training Data

```
dataset:  6 months, Rubixe internship
samples:  1 client engagement + 4 independent capstones
domains:  telecom · finance · insurance · public health · epidemiology
labels:   accuracy alone is not a metric you can trust
```

Additional pretraining on a 4-person team build: **Krushi Manch**, a multilingual agricultural platform (PHP/MySQL + HTML/CSS/JS) — 50+ crop profiles, disease guidance, and a rental marketplace, shipped from requirements to a working system.

---

### 📊 Evaluation Results

| Task | Model | Metric | Score |
|---|---|---|---|
| Home Loan Default Prediction | XGBoost (tuned) | Accuracy / ROC-AUC | `91.98%` / `0.761` |
| Vaccine Rate Forecasting | Random Forest | R² / MAE | `≈1.0` / `0.77` |
| Customer Churn Prediction | Random Forest + SMOTE | Accuracy | `79%` |
| Insurance Claim Prediction | Logistic Regression | Accuracy / ROC-AUC | `84.7%` / `~0.50` |
| COVID-19 Case Forecasting | Ridge Regression | Best baseline | lowest RMSE |

---

### ⚠️ Known Limitations & Honest Notes

- On the **Insurance Claim** task, accuracy looked great — ROC-AUC exposed that it wasn't. Learned to never trust one metric alone.
- On the **COVID-19 forecasting** task, the tuned model actually *underfit* (R² < 0) compared to the simple baseline. Kept it in the record instead of hiding it — that's the real lesson, not the polished win.
- Still in active fine-tuning on **Deep Learning** and advanced ML — this model is not frozen.

---

### 🧰 Compatible Tools

<p>
<img src="https://img.shields.io/badge/Python-306998?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/XGBoost-0B6E4F?style=flat-square" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

---

### 📈 Model Performance Summary

<table align="center">
<tr>
<td align="center" width="140">
<h3>91.98%</h3>
<sub>best model accuracy<br>(Home Loan Default)</sub>
</td>
<td align="center" width="140">
<h3>6</h3>
<sub>end-to-end projects<br>shipped</sub>
</td>
<td align="center" width="140">
<h3>5</h3>
<sub>domains covered<br>(telecom → epidemiology)</sub>
</td>
<td align="center" width="140">
<h3>95%</h3>
<sub>NASSCOM Gold<br>certification score</sub>
</td>
</tr>
</table>

---

### 📮 Citation / Contact

If you'd like to deploy this model on your team, or just talk data:

<p>
<a href="mailto:hirenkeraliya99@gmail.com"><img src="https://img.shields.io/badge/Email-hirenkeraliya99%40gmail.com-c53a5f?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/hiren-keraliya-440700259/"><img src="https://img.shields.io/badge/LinkedIn-Connect-2f6fed?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/hiren223"><img src="https://img.shields.io/badge/GitHub-Explore_Repos-1b2330?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

<p align="center"><sub>⚠️ This model occasionally overfits to good coffee and underperforms before 9 AM.</sub></p>
