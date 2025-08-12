Data Analytics Intermediate Project
# Fraud-Detection-in-Financial-Transaction

## 📌 Overview
This project focuses on analyzing financial transactions to uncover **patterns of fraudulent activity**.  
Using **data analytics techniques**, we explore the dataset, visualize trends, and gain insights into how fraud differs from legitimate transactions.  
We also introduce a simple machine learning model to demonstrate how analytics can enhance fraud prevention.

---

## 📂 Dataset
- **Source:** [Credit Card Fraud Detection Dataset - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Transactions:** 284,807  
- **Fraud Cases:** Only 0.172% of the dataset (highly imbalanced)  
- **Features:**
  - `Time` — seconds elapsed between transactions
  - `V1`–`V28` — anonymized PCA-transformed features
  - `Amount` — transaction value
  - `Class` — `0` = Legitimate, `1` = Fraud

---

## 📊 Project Workflow
1. **Data Loading & Cleaning**
   - Check for missing values
   - Handle imbalanced dataset
2. **Exploratory Data Analysis (EDA)**
   - Distribution of fraud vs non-fraud transactions
   - Transaction amount comparison
   - Time-based trends
3. **Visualization**
   - Bar charts, histograms, correlation heatmaps
   - Fraud frequency trends
4. **Basic Predictive Modeling**
   - Train/test split
   - Random Forest Classifier for fraud detection
5. **Key Insights**
   - Fraud transactions often have smaller amounts
   - Fraud is not uniformly distributed across time

---

## 🛠 Technologies Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-learn (Basic ML for demo)
- Imbalanced-learn (SMOTE for handling imbalance)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection-analytics.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run all cells to see analysis and results.

---

## 🤝 Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

---

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

---

## 👩‍💻 Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)
