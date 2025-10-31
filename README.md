# Loan_Repaypent
Choose a bank loan based on key insights offered from three different banks.

---

# 🧮 Loan Repayment Analysis — Excel Project

## 📘 Project Overview

Mr. Hira has received **loan offers from three banks** and wants to identify the **most cost-effective and budget-friendly option** based on key loan insights.
This Excel project analyzes the loan data and calculates:

1. **Monthly Payment (EMI)**
2. **Total Cost of Loan**
3. **Total Interest Amount**

---

## 📂 Dataset Information

**File Name:** `loan_repayment.xlsx`
The workbook contains two sheets:

### **1. Loan Details**

| Bank                 | CBI Bank     | Left Join Bank | Y Axis Bank  |
| -------------------- | ------------ | -------------- | ------------ |
| Loan Amount          | 1,500,000.00 | 1,500,000.00   | 1,500,000.00 |
| Annual Interest Rate | 15.00%       | 12.50%         | 11.00%       |
| Loan Period (Years)  | 5            | 8              | 10           |

---

## 🧠 Task Summary

Using Excel formulas, the following insights are derived from the data:

### **Insight 1: Monthly Payment (EMI)**

This determines how much Mr. Hira must pay each month.

**Excel Function Used:**

```excel
= -PMT(Annual_Interest_Rate/12, Loan_Period_in_Years*12, Loan_Amount)
```

* `Annual_Interest_Rate / 12` → Monthly interest rate
* `Loan_Period_in_Years * 12` → Total number of monthly payments
* `Loan_Amount` → Principal loan amount

> ⚠️ The `PMT()` function returns a **negative value**, so a negative sign is added to make it positive.

---

### **Insight 2: Total Cost of Loan**

Total amount Mr. Hira will repay by the end of the loan period.

**Formula:**

```excel
= Monthly_Payment * (Loan_Period_in_Years * 12)
```

---

### **Insight 3: Total Interest Amount**

The total cost of borrowing the money — the difference between the total amount paid and the original loan amount.

**Formula:**

```excel
= Total_Cost_of_Loan - Loan_Amount
```

---

## ✅ Verification Step

Before finalizing, cross-check the calculated values with the provided **“Loan_repayment_template.pdf”** to ensure all formulas and outputs match.

---

## 💡 Analysis Summary

After calculating EMI, Total Cost, and Total Interest for each bank, the findings are summarized as follows (example summary — update with your actual results):

| Bank               | EMI (Monthly) | Total Cost | Total Interest | Within ₹25,000 Budget? |
| ------------------ | ------------- | ---------- | -------------- | ---------------------- |
| **CBI Bank**       | ₹35,718       | ₹2,143,068 | ₹643,068       | ❌                      |
| **Left Join Bank** | ₹20,320       | ₹1,951,000 | ₹451,000       | ✅                      |
| **Y Axis Bank**    | ₹17,765       | ₹2,131,800 | ₹631,800       | ✅                      |

---

## 🏦 Recommendation

Based on the analysis and considering Mr. Hira’s **monthly repayment budget of ₹25,000**,
**Left Join Bank** offers the **most suitable loan option**, providing:

* An affordable EMI within the budget
* A lower total cost compared to other options
* Reasonable interest rate and loan term balance

---

## 🧰 Tools & Skills Demonstrated

* **Microsoft Excel** (Formulas, PMT Function, Logical Analysis)
* **Financial Modeling** (Loan Repayment Calculations)
* **Data Interpretation**
* **Decision Support Analysis**

---

## 📑 Files in this Repository

| File Name                     | Description                                     |
| ----------------------------- | ----------------------------------------------- |
| `loan_repayment.xlsx`         | The main Excel workbook containing the analysis |
| `Loan_repayment_template.pdf` | Reference template for result verification      |
| `README.md`                   | Project documentation (this file)               |

---

## 🧭 Author

**Razia Sultana**
📍 Dhaka, Bangladesh
💼 Data Analysis | Excel | Financial Modeling
🔗 www.linkedin.com/in/razia-sultana-bd | https://github.com/Razia-Sultana-Coder

---
