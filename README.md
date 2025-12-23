# U.S. Health Outcomes Analysis Using CDC PLACES Data

This project analyzes county-level U.S. health outcomes using the CDC PLACES dataset to
understand how behavioral and clinical risk factors relate to disability, obesity,
depression, and binge drinking. The analysis combines exploratory data analysis,
statistical modeling, and machine learning to surface geographic and behavioral patterns
in public health outcomes.

The goal of the project is to demonstrate end-to-end data science skills, from data
cleaning and feature engineering to modeling, visualization, and interpretation.

---

## My Contributions

I focused on the modeling, analysis, and visualization components of the project, including:

- Building **Random Forest regression models** to predict disability prevalence from behavioral risk factors
- Evaluating **feature importance** to identify dominant predictors such as obesity and inactivity
- Creating **ranked state-level visualizations** highlighting regional health disparities
- Generating comparative plots to analyze relationships between obesity, depression,
  binge drinking, and disability
- Interpreting model outputs and visual trends to draw actionable insights from the data

---

## Key Findings

- Obesity is the strongest positive predictor of disability across both state and county levels
- Physical inactivity and smoking compound disability risk even at similar obesity levels
- Binge drinking shows an inverse relationship with disability and obesity in several regions
- Clear geographic patterns emerge, with higher disability and obesity rates in Southern states

---

## Data & Methods

- **Dataset:** CDC PLACES 2023 (county-level, age-adjusted prevalence data)
- **Preprocessing:** Data cleaning, filtering, and transformation into analysis-ready tables
- **Models:** Random Forest Regression, Linear Regression, Logistic Regression
- **Analysis:** Feature importance, correlation analysis, and geographic comparisons
- **Visualization:** Ranked bar charts, scatter plots, and comparative visual analytics

---

## Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- Jupyter Notebook
- Data Visualization Libraries (Matplotlib / Seaborn)

---

## Notes

This project was developed collaboratively as part of **CS 418 (Introduction to Data Science)**
at the University of Illinois Chicago. This repository is a fork used to document and
present my individual contributions.
