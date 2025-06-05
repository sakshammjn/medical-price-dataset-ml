# Linear Regression Assessment

This repository contains a Python implementation of the Linear Regression algorithm built from scratch using **NumPy**, **Pandas**, and **Matplotlib** for visualization.

---

## Assessment Description

The goal of this assessment is to implement Linear Regression without using any machine learning libraries. The model is trained to predict medical insurance charges based on features such as age, sex, BMI, number of children, smoking status, and region.

---

## Dataset

The dataset used is the **Medical Price Dataset** (`Medical Price Dataset.csv`), which contains:

- `age`
- `sex` (encoded)
- `bmi`
- `children`
- `smoker` (encoded)
- `region` (encoded)
- `charges` (target variable)

---

## Implementation Details

- Data preprocessing includes encoding categorical variables and splitting the dataset into training and testing sets.
- The Linear Regression model is implemented from scratch using the normal equation method.
- Model performance is evaluated using Mean Squared Error (MSE) and R² score.
- Visualization includes a line graph comparing predicted vs actual insurance charges.

---

## Usage

To run the notebook, ensure you have the following packages installed:

```bash
pip install numpy pandas matplotlib notebook

---

**Author:** Saksham Mahajan  
**Date:** June 2025  
**Contact:** sakshammahajan2004@gmail.com
