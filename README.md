### **README for Fraudulent Transaction Prediction Project**

---

# **AI Fraud Transaction Prediction Assistant**

This project implements an **AI-powered Fraud Transaction Prediction Assistant** leveraging machine learning techniques. It uses the **Fraudulent Transactions Prediction dataset** to classify transactions as fraud or not.

---

# **Dataset**

Considering the size of the dataset used, it cannot be uploaded in the github. 
The dataset source link for reference - https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction

# **About Dataset**

**step** - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

**type** - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

**amount** - amount of the transaction in local currency.

**nameOrig** - customer who started the transaction

**oldbalanceOrg** - initial balance before the transaction

**newbalanceOrig** - new balance after the transaction

**nameDest** - customer who is the recipient of the transaction

**oldbalanceDest** - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

**newbalanceDest** - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

**isFraud** - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

**isFlaggedFraud** - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

---

## **Dependencies**

Install the following libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `seaborn`
- `matplotlib`

Install them via:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

---

## **Model and Techniques**

### **Machine Learning**:
- **Algorithm**:
- **Data Preprocessing**:
- **Evaluation**:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - Precision, Recall, F1-Score

### **Visualization**:
- **Correlation Heatmap**: Understand feature relationships.
- **Pie Chart**: Represent probability distribution.

---

## **Developer**

| **Name**                   | **Contact**                   | **GitHub**                              | **LinkedIn**                                     |
|----------------------------|-------------------------------|-----------------------------------------|-------------------------------------------------|
| Gayathri R                 | gayathriramesh04@gmail.com      | [GitHub](https://github.com/Gayathri-R-04/) | [LinkedIn](https://www.linkedin.com/in/gayathri-r-14rg) |

---

**Fraud has no hiding place in a world driven by intelligent insights.**
