# Customer Sales Exploratory Data Analysis (EDA)

### Python | Pandas | NumPy | Matplotlib | Seaborn

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a customer sales dataset to identify purchasing patterns across different demographic and product categories.

The project focuses on data cleaning, handling missing values, removing duplicate records, data aggregation, and visualizing sales trends using Python libraries.

The Jupyter Notebook contains step-by-step explanations, executed code, charts, and findings. Some visualizations are intentionally repeated to demonstrate different plotting approaches and formatting techniques learned during the project.

## Objectives

- Explore and understand the sales dataset.
- Identify and handle missing values and duplicate records.
- Analyze purchasing patterns across gender, age groups, states, occupations, product categories, and marital status.
- Compare sales performance across customer segments.
- Present findings through meaningful visualizations.

## Technologies Used

- **Python:** Data analysis and processing
- **Pandas:** Data cleaning, manipulation, and aggregation
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualization
- **Seaborn:** Statistical and categorical visualizations
- **Jupyter Notebook / VS Code:** Development environment

## Dataset Information

The original dataset contains **11,251 rows and 15 columns**.

During data inspection and cleaning:

- 12 records were found with missing sales amounts.
- 8 exact duplicate records were identified.
- Two entirely empty columns were removed.
- After excluding missing-amount records and exact duplicates, **11,231 records remained**.

The dataset includes customer demographic information, product categories, order quantities, and sales amounts.

**Dataset availability:** The original CSV was provided as part of a training exercise. It is not included in this public repository because redistribution permission has not been independently confirmed.

## Analysis Performed

### 1. Data Exploration and Cleaning
- Inspecting dataset dimensions and structure
- Checking missing values
- Removing irrelevant columns
- Handling missing sales amounts
- Removing duplicate records
- Preparing the dataset for analysis

### 2. Gender-wise Sales Analysis
Examining customer distribution and comparing total recorded spending across gender categories.

### 3. Age Group Analysis
Understanding purchasing patterns across different age groups.

### 4. State-wise Sales Analysis
Identifying the states contributing the highest total recorded sales.

### 5. Occupation-wise Sales Analysis
Comparing recorded sales amounts across occupation categories.

### 6. Product Category Analysis
Analyzing the contribution of different product categories to total sales.

### 7. Marital Status Analysis
Comparing recorded spending across marital-status categories.

## Key Findings

Based on the verified cleaned dataset:

- **Gender:** Female-labelled records contributed the larger share of total sales.
- **Age Group:** Customers aged 26–35 contributed the highest total recorded spending.
- **State:** Uttar Pradesh recorded the highest sales amount.
- **Occupation:** IT Sector contributed the highest sales amount.
- **Product Category:** Food was the leading category by total recorded sales.
- **Marital Status:** Single-labelled records contributed the higher total sales amount.

These findings describe the supplied dataset and should not be interpreted as general purchasing trends across the entire population.

## Visualizations

The notebook contains multiple visualizations, including:

- Count plots
- Bar charts
- Pie charts
- Comparative categorical visualizations

Some visualizations are repeated intentionally to demonstrate improvements in chart formatting, labeling, and presentation.

**The notebook includes saved analysis outputs and charts so that visitors can review the findings directly on GitHub.**

## Project Files

`customer_sales_eda_verified.ipynb` — Main Jupyter Notebook containing the analysis, explanations, charts, and findings.

`README.md` — Project documentation.

## How to Run the Project

1. Download or clone this repository.
2. Open `customer_sales_eda_verified.ipynb` in VS Code or Jupyter Notebook.
3. Install the required Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.
4. Obtain an appropriately authorized copy of the dataset and place it in the notebook's working directory as `sales_data (4).csv`.
5. Select a Python kernel.
6. Run the notebook cells from top to bottom.

**Note:** The original CSV is not distributed with this repository. The saved outputs and visualizations can still be viewed on GitHub without running the notebook. Re-executing the analysis requires access to the dataset.

## Skills Demonstrated

- Data exploration and preprocessing
- Missing-value and duplicate handling
- Pandas DataFrame operations
- Data aggregation using `groupby()`
- Exploratory Data Analysis
- Data visualization using Matplotlib and Seaborn
- Interpreting and communicating analytical findings

## Project Limitations

The analysis is descriptive and based on the supplied training dataset. Differences in the number of records across customer groups may affect comparisons of total sales. The project does not establish causal relationships.

## Conclusion

This project helped me strengthen my practical understanding of Python data analysis libraries, data preprocessing, exploratory analysis, and data visualization.

It also provided hands-on experience in converting raw data into meaningful insights through charts and grouped summaries.
