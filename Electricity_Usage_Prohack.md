# Data Science Bootcamp – Capstone Project 3

## Disclaimer
This project is created for educational purposes as part of the Data Science Bootcamp. The datasets and scenarios are simulated to help learners practice advanced data cleaning, regression, and optimization techniques.

---

## Project Overview
Capstone Project 3 consists of **two main tasks**:

### 1. Data Cleaning: Electricity Contract Selection
You are provided with hourly electricity usage data from a smart meter. The goal is to clean, structure, and analyze the data to determine which electricity contract minimizes annual cost.  

**Electricity Contract Types:**
- **No Flex:** Constant cost per kWh  
- **Monthly Flex:** Cost varies by month  
- **Hourly Flex:** Cost varies by hour  

**Objectives:**
- Perform step-by-step data cleaning in Python  
- Calculate average hourly usage and monthly usage metrics  
- Determine peak usage periods  
- Compute annual costs for each contract type  
- Answer multiple-choice questions about usage patterns and cost analysis  

**Deliverables (task1.zip):**
1. Jupyter Notebook (*.ipynb) with full implementation and outputs  
2. HTML version of the notebook  
3. requirements.txt showing used packages  
4. Python version and OS environment details  

**Sample Questions:**
1. Average hourly electricity usage?  
2. Average usage in February?  
3. Day of week with highest usage?  
4. Highest electricity usage over continuous 4-hour period?  
5. Annual cost under Monthly Flex contract?  
6. Optimal contract type based on historic usage?

---

### 2. McKinsey & Company Prohack: Achieve Singularity
You receive a dataset representing intergalactic energy consumption and well-being indices. The task involves **predicting a composite index** and **optimally allocating energy resources** across galaxies.  

**Objectives:**
1. **Prediction (Regression)**
   - Predict the well-being index (`y`) using all features
   - Steps include:
     - Data cleaning
     - Preprocessing
     - EDA (Exploratory Data Analysis)
     - Feature engineering & selection
     - Modeling
     - Performance evaluation (RMSE)

2. **Optimization**
   - Allocate 50,000 zillion DSML energy units to maximize well-being
   - Constraints:
     - Max 100 zillion per galaxy, min 0 zillion
     - Galaxies with index < 0.7 must get at least 10% of total energy
   - Compute potential and likely increase in the index using provided formulas

**Evaluation Metric:**
- Combined scaled metric:  
  `0.8 * RMSE_prediction + 0.2 * RMSE_optimization * lambda`  
  where `lambda` is a normalizing factor

**Deliverables (task2.zip):**
1. Jupyter Notebook (*.ipynb) with implementation and outputs  
2. HTML version of the notebook  
3. requirements.txt with packages used  
4. submission.csv with:
   - `index`: Unique index from test dataset  
   - `pred`: Predicted well-being index  
   - `opt_pred`: Optimal energy allocation  

---

## Tools & Techniques
- Python 3.x  
- pandas, numpy, matplotlib, seaborn for data cleaning & visualization  
- scikit-learn for regression modeling  
- Optimization algorithms (e.g., linear programming or custom allocation)  
- HTML exports of notebooks for reporting

---

## Skills Demonstrated
- Advanced data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering & selection  
- Regression modeling & evaluation  
- Constraint-based optimization  
- Problem-solving in multi-step, real-world-like scenarios  

---


