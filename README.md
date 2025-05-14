# 📈 Predictive Analysis of Customer Lifetime Value (CLTV) and Policy Preferences in the Insurance Industry

This capstone project explores how insurance companies can use machine learning and clustering to predict **Customer Lifetime Value (CLTV)** and understand **policy preferences** using demographic, financial, and behavioral data. Developed as part of the MSc in Data Science at Dalarna University.

---

## 🎯 Project Objectives

- Predict CLTV using classification models based on customer profiles.
- Explore policy preferences and key predictors such as income, vintage, and area.
- Segment customers using unsupervised clustering (K-Means + PCA).
- Visualize trends and insights to support marketing and retention strategies.

---

## 📂 Project Contents

| File | Description |
|------|-------------|
| `Kushmi- BI Final Project.ipynb` | 💻 Main Python notebook with full modeling and visualization |
| `train_LifeTimePrediction2.csv` | 📊 Training data with customer demographics, income, policy info |
| `test_LifeTimePrediction.csv` | 📈 Test data used for predictions |
| `BI_Project Proposal_Kushmi.pdf` | 📄 Project proposal outlining goals, research question |
| `BI_FinalProject_Kushmi.pdf` | 🧾 Final report with background, EDA, models, results, and literature review |

---

## 📊 Data Source

- **Kaggle Dataset**: [Customer Lifetime Value Prediction](https://www.kaggle.com/datasets/shivamshinde123/customer-life-time-prediction)
- Fields include: `Gender`, `Area`, `Qualification`, `Income`, `Marital Status`, `Vintage`, `Claim Amount`, `Num Policies`, `Policy Type`

---

## 🧪 Methods Used

### 🔍 Preprocessing
- Missing value removal
- Label Encoding of categorical features
- Standard scaling of numerical fields (e.g., vintage, claim amount)

### 📊 EDA
- Correlation matrix
- CLTV distribution
- Claim amount vs area
- Income vs policy distribution
- Vintage vs claim trend

### 🔁 Classification Models
- Logistic Regression
- Decision Tree
- Random Forest (used for feature importance)

### 🔹 Unsupervised Clustering
- K-Means (optimal k via Elbow method)
- Principal Component Analysis (PCA) for 2D visualization

---

## 📈 Visual Highlights

- 📌 Correlation Matrix & Distribution Graphs
- 💡 CLTV by income group
- 🌍 Claim amounts by area
- 📉 Elbow plot to find optimal cluster count
- 🎯 PCA visualization of K-Means clusters

---

## 🛠️ Technologies & Libraries

- `Python`, `Pandas`, `NumPy`
- `scikit-learn` (models, preprocessing, PCA)
- `matplotlib`, `seaborn` (EDA, visualization)

---

## 🚀 How to Run This Project

1. Clone this repo:
```bash
git clone https://github.com/kushitec15691/insurance-cltv-prediction

