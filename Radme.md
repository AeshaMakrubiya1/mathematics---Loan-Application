# 📊 Loan Applications Analysis

## 📌 Project Overview

This project focuses on analyzing a loan applications dataset using concepts from Statistics, Probability, Data Visualization, and Linear Algebra. The objective is to derive meaningful insights from customer loan data and evaluate factors influencing loan approval and default risk.

---

## 🎯 Objectives

* Calculate measures of central tendency (Mean, Median, Mode).
* Analyze data dispersion using Range, Variance, and Standard Deviation.
* Apply probability concepts to estimate loan default risk.
* Compute conditional probabilities based on customer credit scores.
* Visualize data distributions using histograms and Q-Q plots.
* Evaluate skewness and kurtosis of financial variables.
* Perform basic linear algebra operations on financial vectors.
* Generate business insights from the dataset.

---

## 📂 Dataset Description

The dataset contains **5000 loan application records** with the following attributes:

| Column Name      | Description                              |
| ---------------- | ---------------------------------------- |
| Customer_ID      | Unique customer identifier               |
| Age              | Customer age                             |
| Gender           | Customer gender                          |
| Income           | Annual income                            |
| Credit_Score     | Credit score (300–850)                   |
| Employment_Years | Years of employment                      |
| Loan_Amount      | Requested loan amount                    |
| Loan_Term        | Loan duration (months)                   |
| Default_Status   | Indicates whether the customer defaulted |

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Jupyter Notebook

---

## 📈 Analysis Performed

### 1. Central Tendency

* Mean Income
* Median Income
* Mode Income

### 2. Dispersion Measures

* Range
* Variance
* Standard Deviation

### 3. Probability Analysis

* Probability of Loan Default
* Conditional Probability:

  * P(Default | Credit Score < 600)

### 4. Data Visualization

* Credit Score Histogram
* Gaussian Distribution Curve
* Q-Q Plot for Income Distribution

### 5. Statistical Measures

* Skewness
* Kurtosis

### 6. Linear Algebra Operations

* Dot Product
* Vector Norm
* Angle Between Vectors

---

## 📊 Expected Insights

* Customers with lower credit scores generally have higher default risk.
* Income distribution can be analyzed for normality.
* Loan amounts show variability across applicants.
* Credit score is an important factor in loan approval decisions.
* Statistical measures help identify trends and outliers.

---

## ▶️ How to Run

### Install Required Libraries

```bash
pip install pandas numpy matplotlib scipy
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```text
Loan_Analysis.ipynb
```

and execute all cells from top to bottom.

---

## 📁 Project Structure

```text
Loan_Applications_Project/
│
├── loan_applications.csv
├── Loan_Analysis.ipynb
├── README.md
└── report.pdf
```

---

## 📋 Sample Output

* Mean, Median, and Mode of customer income
* Probability of loan default
* Conditional probability based on credit score
* Histogram with Gaussian distribution
* Q-Q Plot
* Linear algebra calculations
* Business insights and conclusions

---

## 📚 Concepts Covered

* Descriptive Statistics
* Probability and Conditional Probability
* Normal Distribution
* Skewness and Kurtosis
* Data Visualization
* Linear Algebra
* Business Analytics

---

## 👨‍💻 Author

Harshil Prajapati

Loan Applications Statistical Analysis Project

---

## 📄 License

This project is created for academic and educational purposes only.
