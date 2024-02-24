# HANDS-ON

## Table of Contents

### PROBLEM STATEMENT

### OBJECTIVE

### AVAILABLE VARIABLE

### EXPERIMENT

### IMPORT PACKAGEE

### DATA FOR PREDICTION

### DATA UNDERSTANDING

### DATA PREPARATION

- **Data Duplicate and Missing checking**
- **Adding relevant variable**
- **Data Transformation**
- **Merging Dataset Predictor**
- **Preparing Dataset for Validation**
    - Import data
    - Adding relevant variable
    - Active status
    - Adding or subtracting product holding
    - Length of credit card ownership
    - Variable removal
    - Variable predictor selection
- Correlation checking
- Splitting Train-Test Data

### Modeling

- **Logistic Regression**
    - Experiment 1
    - Experiment 2
- Gradient Boosting
    - Experiment 1
    - Experiment 2
- Random Forest
    - Experiment 1
    - Experiment 2

### Evaluation

- **Logistic Regression**
    - Experiment 1
    - Experiment 2
- Gradient Boosting
    - Experiment 1
    - Experiment 2
- Random Forest
    - Experiment 1
    - Experiment 2

### Conclusion

## PROBLEM STATEMENT

---

> Concern about delays in credit card payments on FinanKu which will harm business. So that people who have the potential to experience late payments can be predicted more quickly to determine appropriate strategies for dealing with future conditions.
> 

## OBJECTIVE

---

> Create a model that can predict at least 60% of customers who will experience late credit card payments [Accuracy & Recall above 60%]
> 

### AVAILABE VARIABLE

---

From the dataset there are some of available variable.

1. **Customer ID**: Unique ID Customer.
2. **Branch:** Registered customer branch location.
3. **City:** Customer age in year of observation
4. **Age:** Registered customer city location
5. **Avg. Annual Income/Month:** Average annual customer income
6. **Balance (Q1-Q4):** Average sum of money saving that is stored in FinanKu.
7. **Num of Product (Q1-Q4):** Total customer product owner of Finanku.
8. **HasCrCard (Q1-Q4):** The status of credit card ownership (1 = Has, 0 = No).
9. **Unpaid Tagging:** The active status of customer that is observed according to their transaction done.
