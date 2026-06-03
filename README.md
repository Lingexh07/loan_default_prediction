# 💳 Loan Default Prediction System

## 📌 Overview

The **Loan Default Prediction System** is a Data Analytics and Machine Learning project designed to analyze borrower financial data and identify potential loan defaulters.

Financial institutions face significant risks when borrowers fail to repay loans, resulting in financial losses and increased Non-Performing Assets (NPAs). This project uses **Exploratory Data Analysis (EDA)**, **Risk Analysis**, **Linear Regression**, and **Interactive Dashboard Visualization** to understand borrower behavior and support smarter loan approval decisions.

The project demonstrates an end-to-end workflow including:

- Data Collection
- Data Preprocessing
- Statistical Analysis
- Exploratory Data Analysis (EDA)
- Risk Categorization
- Predictive Modeling
- Dashboard Visualization

---

# 🎯 Objectives

The primary objectives of this project are:

- Load and analyze borrower loan data
- Clean and preprocess the dataset
- Perform Exploratory Data Analysis (EDA)
- Identify factors influencing loan defaults
- Analyze borrower risk levels
- Build a Linear Regression model
- Evaluate model performance
- Create interactive visualizations and dashboards
- Support better loan approval strategies

---

# 📂 Dataset Information

## Dataset Source

**Kaggle Lending Club Loan Dataset**

## Features Used

| Feature | Description |
|----------|-------------|
| loan_amnt | Loan amount requested |
| term | Loan duration |
| int_rate | Interest rate |
| annual_inc | Annual income |
| emp_length | Employment length |
| home_ownership | Home ownership status |
| purpose | Purpose of loan |
| grade | Loan risk grade |
| loan_status | Repayment status |

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Plotly | Interactive Dashboard |
| Scikit-learn | Machine Learning |

---

# ⚙️ Project Workflow

## 1️⃣ Data Collection

- Load loan dataset
- Understand dataset structure
- Explore columns and data types

---

## 2️⃣ Data Cleaning & Preprocessing

### Tasks Performed

- Handle missing values
- Remove unwanted symbols
- Convert data types
- Encode categorical variables
- Prepare data for analysis

### Techniques Used

- Label Encoding
- Missing Value Treatment
- String Processing
- Data Type Conversion

---

## 3️⃣ Exploratory Data Analysis (EDA)

EDA helps uncover borrower behavior and loan repayment patterns.

### Analysis Performed

- Loan Amount Distribution
- Annual Income Distribution
- Interest Rate Analysis
- Loan Status Analysis
- Correlation Analysis

---

## 4️⃣ Default Behavior Analysis

### Comparison Between

- Fully Paid Loans
- Charged-Off Loans

### Insights Extracted

- High-risk borrower identification
- Loan repayment trends
- Financial risk indicators

---

## 5️⃣ Group-Based Analysis

### Income vs Default

Analyzes whether lower-income borrowers are more likely to default.

### Employment Length vs Default

Examines the impact of job stability on repayment behavior.

### Loan Purpose vs Default

Compares default rates across different loan purposes.

### Home Ownership vs Default

Studies repayment behavior based on housing ownership status.

---

## 6️⃣ Relationship Analysis

Relationships explored include:

- Loan Amount vs Default
- Interest Rate vs Default
- Annual Income vs Loan Amount
- Interest Rate vs Risk Category

---

# 📊 Data Visualization

Several visualizations were created to better understand borrower behavior.

| Visualization | Purpose |
|--------------|---------|
| Bar Charts | Default distribution analysis |
| Histograms | Income and loan distributions |
| Scatter Plots | Relationship analysis |
| Box Plots | Outlier detection |
| Heatmaps | Correlation analysis |

---

# ⚠️ Risk Analysis

Borrowers are categorized into:

- 🟢 **Low Risk**
- 🟡 **Medium Risk**
- 🔴 **High Risk**

### Risk Factors Considered

- Interest Rate
- Annual Income
- Loan Grade
- Loan Characteristics

This classification helps identify potential defaulters before loan approval.

---

# 🤖 Machine Learning Model

## Linear Regression

The project uses a Linear Regression model for predictive analysis.

### Independent Variables

- annual_inc
- int_rate
- term

### Dependent Variable

- loan_amnt

---

# 📈 Model Evaluation

The model performance is measured using:

| Metric | Description |
|----------|-------------|
| R² Score | Measures prediction accuracy |
| MAE | Mean Absolute Error |
| MSE | Mean Squared Error |

---

# 📊 Interactive Dashboard

Interactive visualizations are developed using Plotly.

## Dashboard Features

- Loan Distribution Analysis
- Income vs Loan Amount
- Default Comparison
- Risk Category Analysis
- Interactive Filtering
- Dynamic Charts

---

# 📁 Project Structure

```bash
loan-default-prediction/
│
├── loan_default_prediction.py
├── README.md
├── requirements.txt
└── dataset.csv
```

---

# ▶️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/loan-default-prediction.git
```

## Navigate to Project Directory

```bash
cd loan-default-prediction
```

## Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

---

# 🚀 Run the Project

```bash
python loan_default_prediction.py
```

---

# 📌 Sample Outputs

The system generates:

- Default Distribution Charts
- Income Analysis Graphs
- Correlation Heatmaps
- Risk Classification Results
- Loan Predictions
- Interactive Dashboard Visualizations

---

# 🔍 Key Insights

- Higher interest rates are associated with increased default risk.
- Borrowers with lower annual incomes show higher repayment challenges.
- Employment stability positively impacts repayment behavior.
- Loan purpose influences default probability.
- Risk categorization helps financial institutions identify potential defaulters efficiently.

---

# 🔮 Future Enhancements

Potential future improvements include:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Model
- Streamlit Web Application
- Real-Time Risk Dashboard
- Cloud Deployment
- Advanced Credit Scoring System

---

# 🎓 Learning Outcomes

This project provides practical experience in:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning Workflow
- Regression Modeling
- Data Visualization
- Financial Risk Analytics
- Dashboard Development

---

# ✅ Conclusion

The **Loan Default Prediction System** demonstrates how Data Analytics and Machine Learning can assist financial institutions in identifying risky borrowers and improving credit risk management.

By combining EDA, predictive modeling, risk categorization, and interactive dashboards, the project delivers meaningful insights into borrower financial behavior and loan repayment patterns.

This project serves as an excellent example of applying analytics and machine learning techniques to solve real-world financial problems.

---

# 👨‍💻 Author

**Mukesh Krishna**

**BCA (Artificial Intelligence & Machine Learning)**

Python | Java | Machine Learning | Data Analytics | UI/UX Design | Web Development

---

# 📜 License

This project is developed for **educational and academic purposes**.

Feel free to use, modify, and enhance it for learning and research.
