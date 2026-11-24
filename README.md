# Supermarket Sales Analysis and Machine Learning

## Project Overview
This project analyses supermarket sales data to identify sales trends, customer purchasing patterns, product performance, and business insights. It also applies machine learning techniques to explore the prediction of sales, transaction quantities, and customer spending categories.

## Objectives
- Analyse supermarket sales performance.
- Identify top-performing product lines and branches.
- Examine customer purchasing patterns and payment preferences.
- Develop machine learning models for sales and quantity prediction.
- Classify transactions into low, medium, and high spending categories.
- Evaluate model performance and identify limitations.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models
The project explores:
- Linear Regression
- Random Forest Regression
- Random Forest Classification

Models were evaluated using metrics such as MAE, MSE, R² score, accuracy, precision, recall, and F1-score.

## Dataset
The project uses a supermarket sales dataset containing 1,000 transactions from three branches in Myanmar. The dataset includes product information, unit prices, quantities, sales, customer details, payment methods, and transaction dates.

## Key Findings
- Total recorded revenue was approximately 322,966.75.
- Food and beverages generated the highest revenue among the product lines.
- Random Forest achieved an R² score of approximately 0.999 when predicting sales using unit price and quantity.
- Removing unit price and quantity significantly reduced sales prediction performance.
- Spending-category classification achieved 41% accuracy.

## Project Structure
- `notebooks/` – Data analysis, visualisations, and machine learning experiments.
- `data/` – Dataset files.
- `report/` – Final project report.

## Authors
- Akubueze Chibikem Henry
- Miracle Nnadike
- Chukwuneke Kachisicho Amanda
- Abolaji Gbolahan
- Yusuf Oluwadahunsi

## Conclusion
This project demonstrates how data analysis and machine learning can be applied to supermarket sales data to uncover business insights and investigate predictive capabilities. It also highlights the importance of feature selection and careful model evaluation.
