#  Insurance Benefit Modeling & Privacy Protection

This project addresses four real-world tasks for a U.S.-based insurance company using machine learning and data science techniques. The focus includes prediction, classification, and protecting personal data from misuse while preserving model quality.

---

##  Objective

1. **Customer Similarity:** Use k-NN to identify similar clients for targeted marketing.
2. **Benefit Classification:** Predict whether a new client will receive an insurance benefit (binary classification).
3. **Benefit Amount Prediction:** Use linear regression to estimate the number of insurance benefits.
4. **Data Protection:** Apply data transformation (linear algebra-based) to protect personal information while preserving model performance.

---

##  Dataset Description

- **Source:** insurance_us.csv
- **Features:**
  - `sex`: Gender of the client
  - `age`: Age in years
  - `income`: Annual income
  - `children`: Number of family members
- **Target:**
  - `benefits`: Number of insurance benefits received over the last 5 years

---

##  Project Workflow

1. **Exploratory Data Analysis**
   - Check for missing values and outliers
   - Understand feature distributions

2. **Task 1 – Similarity Search**
   - Implement k-NN to find nearest clients

3. **Task 2 – Classification**
   - Compare dummy classifier with k-NN classifier
   - Use F1-score to evaluate
   - Handle class imbalance using RandomOverSampler and RandomUnderSampler

4. **Task 3 – Regression**
   - Train a linear regression model to predict benefit amount
   - Evaluate with RMSE and R²

5. **Task 4 – Privacy Masking**
   - Apply matrix transformation to protect features
   - Ensure model performance remains consistent after transformation

---

##  Key Insights

- Machine learning provides measurable improvements over baseline (dummy) models.
- Class balancing improves classification performance.
- Privacy transformation via matrix multiplication can be effective and safe.
- k-NN is useful for similarity-based customer targeting.

---

##  Project Structure

```
insurance-benefit-modeling/
│
├── insurance_benefit_modeling.ipynb
├── insurance_us.csv
├── requirements.txt
└── README.md
```
---

##  Tools & Libraries Used

- Python
- pandas
- numpy
- seaborn
- scikit-learn
- imbalanced-learn

---

##  Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *ML Pipelines, Classification, and Data Protection*

---

##  Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
