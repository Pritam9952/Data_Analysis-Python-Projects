# 📊 Financial Loan Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=flat&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-yellow?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red?style=flat&logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualizations-9cf?style=flat&logo=seaborn)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 📌 Project Overview

This project performs **Financial Loan Analysis** using Python to uncover insights, patterns, and relationships within customer loan data.  
It involves **data cleaning**, **exploratory data analysis (EDA)**, **visualizations**, and **feature engineering** to identify trends and improve financial decision-making.

The goal of this project is to **analyze loan data** and help stakeholders **predict defaults, understand borrower behavior, and optimize risk assessment**.

---

## 📂 Dataset

The dataset contains information about financial loan applications and customer demographics.  
Key attributes include:

| Feature Name        | Description |
|---------------------|------------|
| `loan_id`          | Unique ID for each loan |
| `gender`           | Gender of the applicant |
| `married`          | Marital status |
| `dependents`      | Number of dependents |
| `education`       | Applicant's education level |
| `self_employed`   | Employment status |
| `applicant_income`| Monthly income of the applicant |
| `loan_amount`    | Loan amount requested |
| `loan_status`    | Loan approval status (Approved/Rejected) |

> **Note:** Dataset paths are defined inside the Jupyter Notebook.

---

## 🚀 Tech Stack

- **Programming Language:** Python 🐍  
- **Data Analysis & Cleaning:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn  
- **Feature Engineering:** Scikit-learn, Encoding techniques  
- **Environment:** Jupyter Notebook (`.ipynb`)  

---

## 📈 Project Workflow

### **1. Data Import & Setup**
- Load libraries
- Import dataset
- Configure environment

### **2. Data Cleaning**
- Handle missing values
- Remove duplicates
- Fix data types

### **3. Exploratory Data Analysis (EDA)**
- Understand distributions
- Detect patterns & correlations
- Compare loan status with key features

### **4. Feature Engineering**
- Encoding categorical variables
- Scaling numeric features
- Preparing data for modeling

### **5. Data Visualization**
- Univariate & bivariate analysis  
- Loan approval trends  
- Heatmaps & boxplots for key insights

### **6. Results & Insights**
- Summarize findings  
- Share key metrics  
- Recommend business strategies

---

## 📊 Visualizations

| Visualization Type | Purpose |
|--------------------|---------|
| **Bar Charts** | Loan approvals by gender, education, etc. |
| **Heatmaps** | Correlation between features |
| **Boxplots** | Outlier detection |
| **Histograms** | Income & loan amount distribution |

---

## 📂 Project Structure

```
financial-loan-analysis/
│
├── financial_loan.ipynb          # Original notebook
├── README.md                     # Project documentation
├── dataset/                      # Place dataset here
├── images/                       # Optional - Store visualizations
└── requirements.txt              # Required dependencies
```

---

## 🛠 Installation & Usage

### **1. Clone the Repository**
```bash
git clone https://github.com/<pritam9952>/financial_loan_Project.git
cd financial-loan-analysis
```

### **2. Create a Virtual Environment (Optional but Recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Run the Notebook**
```bash
jupyter notebook financial_loan.ipynb
```

---

## 📌 Results & Key Insights

- High loan approval rates are observed among **salaried applicants**.
- Applicants with **higher incomes** have a significantly **lower default probability**.
- **Loan amount** and **credit history** play a major role in loan approvals.
- Visualizations highlight **key demographic patterns** in loan distribution.

---

## 🤝 Contributing

Contributions are welcome!  
Follow these steps to contribute:

1. **Fork** the repository  
2. Create a **new branch**  
3. **Commit** your changes  
4. **Push** to your fork  
5. Submit a **Pull Request**

---

## 📝 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this code.

---

## 📧 Contact

**Author:** Pritam Nagar  
📍 *Maulana Azad National Institute of Technology, Bhopal*  
📩 Email: *pritamnagar2211@gmail.com*  
🌐 GitHub: [https://github.com/pritam9952](https://github.com/9952)

---

> If you like this project, don't forget to **⭐ star the repo** to support the developer!
