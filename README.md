# Risk Analytics In Banking & Financial Services

## Business Objectives  
The objective of this project is to analyze financial data and identify patterns that indicate whether a client may have difficulty repaying their installments. The insights gained can help financial institutions:  

- **Deny loans** to high-risk applicants  
- **Reduce loan amounts** for risky individuals  
- **Adjust interest rates** based on risk level  
- **Ensure creditworthy consumers are not rejected**  

By performing **Exploratory Data Analysis (EDA)**, we aim to identify **key variables** that indicate loan default, helping companies with risk assessment and portfolio management.

---

## Data Understanding  

The project uses three key datasets:  

1. **application_data.csv**  
   - Contains all client information at the time of application.  
   - Indicates whether a client has payment difficulties.  

2. **previous_application.csv**  
   - Includes details of the client's past loan applications.  
   - Shows whether the application was **Approved, Cancelled, Refused,** or **Unused Offer**.  

3. **columns_description.csv**  
   - A data dictionary explaining all variable meanings.  

---

## Solution Approach  

The project consists of **two Jupyter Notebook files**:  

1. **EDA on `application_data.csv`**  
   - A detailed Exploratory Data Analysis (EDA) to identify important features for predicting defaulters.  

2. **Merging & Analysis of `application_data.csv` & `previous_application.csv`**  
   - Inner join on `SK_ID_CURR` to combine both datasets for deeper insights into loan repayment behavior.  

---

## How to Use  

1. **Clone the repository**  
   ```sh
   git clone https://github.com/yourusername/Risk_Analytics.git
   cd Risk_Analytics
