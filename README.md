# Machine Learning Lab Evaluation

This repository contains a Python notebook for a retail data analysis lab.

## Files

- `lab_evaluaton.ipynb` - Jupyter notebook that performs exploratory data analysis on the Online Retail dataset.
- `Online_Retail.xlsx` - Retail sales dataset used by the notebook.
- `requirements.txt` - Python package requirements for the project.
- `3rd_Exp.py`, `new.py` - other Python files in the workspace.

## Description

The notebook loads retail transaction data and performs several analysis steps, including:

- Loading and previewing dataset rows and columns
- Checking for missing values and duplicate rows
- Calculating revenue for each item
- Identifying top selling products by quantity
- Calculating total revenue and average order value
- Counting unique customers
- Finding the country with the most orders
- Listing products bought together by invoice
- Identifying customers who purchased more than 10 items
- Determining peak shopping hours

## Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the notebook with Jupyter:

```bash
jupyter notebook lab_evaluaton.ipynb
```

## Notes

- The notebook expects `Online_Retail.xlsx` to be present in the same directory.
- Make sure Python and Jupyter are installed in your environment.
