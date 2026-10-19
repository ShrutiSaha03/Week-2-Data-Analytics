# Retail Sales Data Analysis and Prediction

## Project Overview

This project focuses on analyzing retail sales data through data cleaning, exploratory data analysis (EDA), and machine learning. The objective is to transform raw sales data into a structured dataset, identify meaningful business insights, and develop regression models to predict sales amounts.

**Tools and Technologies**
- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Machine Learning: Linear Regression and Random Forest Regression

## Project Tasks

### Task 1: Data Cleaning and Preprocessing

**Objective:** Prepare the raw retail sales dataset for reliable analysis.

**Work performed:**
- Loaded and inspected the dataset.
- Identified and handled missing values.
- Detected and removed duplicate records.
- Corrected invalid age values.
- Standardized column names and data formats.
- Identified potential outliers using the Interquartile Range (IQR) method.
- Prepared a cleaned dataset for further analysis.

**Key results:**
- Initial records: 1,060
- Duplicate records removed: 60
- Final records: 1,000

**Outcome:** Created a cleaner, more consistent dataset for exploratory analysis.

### Task 2: Exploratory Data Analysis (EDA)

**Objective:** Explore the cleaned dataset to understand sales patterns, customer behavior, and product performance.

**Work performed:**
- Calculated descriptive statistics.
- Analyzed sales by product category.
- Examined monthly sales trends.
- Investigated customer ratings and discount patterns.
- Created visualizations, including bar charts, histograms, box plots, and heatmaps.
- Identified unusual sales values and data-quality limitations.

**Key results:**
- Records analyzed: 1,000
- Product categories analyzed: 5
- Gross sales value across the dataset: approximately ₹32.10 million, based on the project's current sales calculation.

**Outcome:** Identified category-level differences, monthly variations, and potential outlier effects on sales analysis.

### Task 3: Sales Prediction Using Machine Learning

**Objective:** Build and evaluate regression models for predicting gross sales amounts using historical retail data.

**Work performed:**
- Selected the prediction target and relevant input features.
- Engineered date-based and other useful features where appropriate.
- Prepared data for model training, including handling missing values and categorical variables.
- Split the data into training and testing sets using an 80:20 ratio.
- Trained and compared Linear Regression and Random Forest Regression models.
- Evaluated models using Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²).
- Created actual-versus-predicted plots and feature-importance visualizations.
- Explored hyperparameter tuning to improve model performance.

**Outcome:** Compared regression models and examined their prediction errors and limitations. The results highlighted the challenges of predicting sales from a small dataset with highly skewed sales values and extreme outliers.

*Note: Final model performance should be reported using the verified outputs from the completed notebook.*

## Dataset

The project uses a retail orders dataset containing information such as:
- Order details and dates
- Customer demographics
- Product categories
- Quantity and unit price
- Discounts and payment methods
- Customer ratings

The gross sales amount is calculated from quantity and unit price in the project's sales analysis. This definition should be distinguished from net sales after discounts or other adjustments.

## Project Structure

```text
Retail-Sales-Analysis/
│
├── README.md
│
├── Task1_Data_Cleaning/
│   ├── Task1.ipynb
│   ├── cleaned_retail_orders.csv
│   └── Task1_Report.pdf
│
├── Task2_Exploratory_Data_Analysis/
│   ├── Task2.ipynb
│   ├── charts/
│   └── Task2_Report.pdf
│
└── Task3_Sales_Prediction/
    ├── Task3.ipynb
    ├── model_comparison.csv
    ├── actual_vs_predicted.png
    ├── feature_importance.png
    └── Task3_Report.pdf
```

*The folder and file names above are suggested examples. Update them to match the files actually included in your repository.*

## Key Learnings

- Data cleaning is essential before drawing business conclusions.
- Missing values, duplicate records, and extreme outliers can affect analytical results.
- EDA helps reveal category-level performance, sales trends, and relationships between variables.
- Machine learning models require suitable features and careful evaluation.
- RMSE, MAE, and R² provide complementary ways to assess regression performance.
- Model results must be interpreted in the context of data quality, dataset size, and the prediction objective.

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from raw data preprocessing to exploratory analysis and machine learning model evaluation. It provided practical experience in Python-based data manipulation, visualization, statistical analysis, feature engineering, and regression modeling.

The project also highlights the importance of validating analytical findings and evaluating model limitations before using predictions to support business decisions.

## Author

**Shruti Saha**
