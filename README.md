# 💼 Employee Salary Prediction using Feedforward Neural Network (FNN)

## 📌 Problem Statement

We aim to predict an employee’s **monthly salary** based on multiple factors:

- Years of Experience  
- Education Score  
- Skill Rating  
- Number of Certifications  

In real-world scenarios, companies estimate salaries using a combination of these attributes rather than manual calculations.

### ✔ Key Observations
- Experience impacts salary growth  
- Higher skills lead to better pay  
- Education contributes to opportunities  
- Certifications add value  

A **Feedforward Neural Network (FNN)** is used to learn these relationships automatically.

---

## 📥 Input and Output

### 🔹 Inputs:
- Experience (Years)  
- Education Score (1–10)  
- Skill Rating (1–10)  
- Certifications Count  

### 🔹 Output:
- Predicted Salary  

---

## 📊 Sample Dataset

| Exp | Edu | Skill | Cert | Salary |
|-----|-----|-------|------|--------|
| 1   | 5   | 4     | 0    | 22000  |
| 2   | 6   | 5     | 1    | 26000  |
| 3   | 6   | 6     | 1    | 32000  |
| 4   | 7   | 7     | 2    | 40000  |
| 5   | 7   | 8     | 2    | 47000  |
| 6   | 8   | 8     | 3    | 54000  |
| 7   | 8   | 9     | 3    | 62000  |
| 8   | 9   | 9     | 4    | 70000  |
| 9   | 9   | 10    | 4    | 75000  |
| 10  | 9   | 10    | 5    | 85000  |

---

## 🧠 Architecture of Neural Network

- **Input Layer:** 4 neurons  
  - Experience  
  - Education  
  - Skill  
  - Certification  

- **Hidden Layer:** 6 neurons  

- **Output Layer:** 1 neuron  
  - Predicted Salary  

### 🔗 Network Structure:
    -4->6->1


---

## ⚙️ Technologies Used

- Python  
- Scikit-learn  
- MLPRegressor (Feedforward Neural Network)  
- StandardScaler (Feature Scaling)  

---

## 🚀 Model Workflow

1. Data Collection  
2. Data Preprocessing (Scaling)  
3. Train-Test Split  
4. Model Training using FNN  
5. Prediction  
6. Performance Evaluation (MAE)  

---

## 📈 Evaluation Metric

- **Mean Absolute Error (MAE)**  
Used to measure the average prediction error.

---

## 🔍 Example Prediction

```python
Input: [5, 8, 9, 3]
Output: Predicted Salary ≈ ₹XXXXX
