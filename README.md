

---

# **Credit Risk Prediction System**
<img width="1440" alt="Screenshot 2024-09-30 at 5 28 28 PM" src="https://github.com/user-attachments/assets/23fb5b5e-60ee-4f9d-a49f-b6ec2268dbd1">
<img width="1440" alt="Screenshot 2024-09-30 at 5 28 57 PM" src="https://github.com/user-attachments/assets/6857f7cc-b461-4c1d-9e92-287800805296">
<img width="1440" alt="Screenshot 2024-09-30 at 5 29 19 PM" src="https://github.com/user-attachments/assets/a6ac74d2-efd5-4c53-9224-068bc0a6039c">
<img width="1440" alt="Screenshot 2024-09-30 at 5 29 48 PM" src="https://github.com/user-attachments/assets/6080caef-107d-413f-9aa5-97b72b69e4dd">




This project aims to predict whether a borrower is likely to default on their credit payment using machine learning techniques. By analyzing financial history, demographic data, and repayment behavior, the model provides predictions that can help financial institutions make informed decisions about credit risk management.

## **Project Overview**

The Credit Risk Prediction System is built using the **UCI Credit Card Default dataset**. It leverages a **Random Forest Classifier** to predict whether a customer will default on their credit payments in the next month. The model is deployed via a **Streamlit** web application, where users can upload datasets or input individual data points for prediction.

## **Features**

- **Credit Risk Prediction**: Predicts the likelihood of a customer defaulting on their payments.
- **Dataset Upload**: Upload new datasets to retrain the model.
- **User Input**: Users can input individual customer details for instant predictions.
- **Model Evaluation**: Displays model performance metrics, including a confusion matrix, classification report, and feature importance.

## **Technologies Used**

- **Python 3.8+**
- **Streamlit** (for the web interface)
- **Scikit-learn** (for the Random Forest model)
- **Pandas** (for data manipulation)
- **Seaborn & Matplotlib** (for data visualization)

## **Dataset**

We used the **UCI Credit Card Default Dataset**, which includes the following key features:
- **LIMIT_BAL**: Amount of given credit (loan).
- **AGE**: Age of the customer.
- **BILL_AMT1 to BILL_AMT6**: Monthly bill amounts for the last 6 months.
- **PAY_AMT1 to PAY_AMT6**: Monthly payment amounts for the last 6 months.
- **PAY_0 to PAY_6**: Repayment status from the last 6 months.

### **Dataset Link**
- UCI Credit Card Default Dataset: [Download here](https://archive.ics.uci.edu/ml/machine-learning-databases/00350/default%20of%20credit%20card%20clients.xls)

## **Setup Instructions**

### **Prerequisites**

Before you begin, ensure you have the following installed:
- Python 3.8+
- Streamlit
- Scikit-learn
- Pandas
- Seaborn
- Matplotlib

### **Installation Steps**

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   cd credit-risk-prediction
   ```

2. **Install Required Libraries**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   ```bash
   streamlit run app.py
   ```

4. **Upload Dataset or Input Customer Details**
   You can upload a new dataset or enter customer information to predict their credit default risk.

### **How to Use the Application**

- **Step 1**: Run the Streamlit application using `streamlit run app.py`.
- **Step 2**: On the sidebar, upload a new dataset or use the demo dataset (UCI Credit Card Default Dataset).
- **Step 3**: Enter customer details manually to predict credit default risk in real-time.
- **Step 4**: View the model evaluation metrics, feature importance, and prediction results on the app interface.

## **Project Structure**

```
.
├── app.py               # Main Streamlit app
├── requirements.txt     # List of dependencies
├── README.md            # This file
└── data/                # Folder for any local datasets
```

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
