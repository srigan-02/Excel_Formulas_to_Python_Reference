# 🧮 Excel Formulas to Python Equivalents

This repository provides a **complete collection of Excel formulas** — translated into **Python equivalents** for data analysis, automation, and financial modeling.  
It also includes **financial functions** such as **NPV**, **Profitability Index (PI)**, **IRR**, and **Payback Period**.

---

## 📘 Project Overview

Excel functions are powerful, but integrating them directly into Python workflows (using `pandas`, `numpy`, or pure logic) enables automation and reproducibility.

This project serves as a **reference guide** and **Python toolkit** for:
- Data analysts transitioning from Excel to Python  
- Finance professionals building automation pipelines  
- Power BI / Data Science teams standardizing Excel logic in Python  

---

## 📂 Repository Contents

| File | Description |
|------|--------------|
| `Excel_Formulas_to_Python_Reference.ipynb` | Jupyter notebook version for interactive exploration |
| `README.md` | Documentation for understanding and usage |

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/excel-formulas-to-python.git
cd excel-formulas-to-python

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

# Install dependencies
pip install pandas numpy numpy-financial

🧾 Example Usage
1️⃣ NPV (Net Present Value)
from Excel_Formulas_to_Python_Reference import npv

cashflows = [-1000, 200, 300, 400, 500]
rate = 0.1
print("NPV:", npv(rate, cashflows))

2️⃣ Profitability Index
from Excel_Formulas_to_Python_Reference import profitability_index

initial_investment = 1000
cashflows = [200, 300, 400, 500]
rate = 0.1
print("PI:", profitability_index(initial_investment, rate, cashflows))

3️⃣ Weighted Average
from Excel_Formulas_to_Python_Reference import weighted_average

values = [10, 20, 30]
weights = [1, 2, 3]
print("Weighted Average:", weighted_average(values, weights))

📊 Categories Covered
Category	Example Excel Formula	Python Equivalent
Math & Stats	=SUM, =AVERAGE, =MEDIAN, =MODE	sum(), numpy.mean(), statistics.median()
Text	=LEFT, =RIGHT, =MID, =LEN	Python string slicing & functions
Dates	=TODAY(), =EDATE, =EOMONTH	datetime & dateutil.relativedelta
Financial	=PMT, =NPV, =IRR, =RATE	Python financial functions
Lookup	=VLOOKUP, =INDEX, =MATCH	Pandas filtering & indexing
Conditional	=IF, =SUMIF, =COUNTIFS	Pandas loc and conditional logic

📈 Financial Functions
npv(rate, cashflows)
profitability_index(initial_investment, rate, cashflows)
irr(cashflows)
payback_period(initial_investment, cashflows)

🧩 Dependencies
Python 3.8+
pandas
numpy
numpy-financial
datetime
re

💡 Contribution

Want to add more Excel-to-Python conversions?
Fork this repository
Create a feature branch
git checkout -b feature/add-new-formula
Add your formula and submit a pull request 🚀

🏆 Author
Sriram G
Data Analyst | Power BI Developer | Finance & Automation Enthusiast


📜 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute this with attribution.
