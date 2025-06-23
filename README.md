
---

## 🧠 Problem Statement

Customer churn is a key issue in many industries, especially banking and telecom. The goal is to predict which customers are likely to leave the service, allowing the business to take preventive actions and improve retention rates.

---

## 📁 Dataset Information

- **Features**:
  - CreditScore
  - Geography
  - Gender
  - Age
  - Tenure
  - Balance
  - NumOfProducts
  - HasCrCard
  - IsActiveMember
  - EstimatedSalary
- **Target**: `Exited` (1 = Churned, 0 = Retained)

> Dataset Source: [Insert source or Kaggle link here]

---

## 🚀 Project Pipeline

### 1. Data Preprocessing
- Handle missing data (if any)
- Encode categorical variables
- Feature scaling (StandardScaler)

### 2. Exploratory Data Analysis (EDA)
- Visualize churn distribution
- Correlation heatmaps
- Feature impact analysis

### 3. Model Building (Deep Learning)
- Sequential Keras model
- Layers: Dense + Activation (ReLU, Sigmoid)
- Loss: Binary Crossentropy
- Optimizer: Adam
- Metric: Accuracy

### 4. Model Evaluation
- Accuracy score
- Confusion matrix
- Classification report (Precision, Recall, F1)

---

## 🧪 Requirements

Install required packages:

```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
