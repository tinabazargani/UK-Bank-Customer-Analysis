# UK Bank Customer Analysis

## Project Overview

This project focuses on analyzing UK bank customer data to identify customer characteristics, account balance patterns, regional distributions, and customer acquisition trends.

The main objective is to perform Exploratory Data Analysis (EDA), extract meaningful business insights, and understand customer behavior patterns using Python data analysis techniques.

---

## Dataset

The dataset contains information about UK bank customers, including demographic, geographic, and financial attributes.

### Dataset Features:

- Customer ID
- Name
- Gender
- Age
- Region
- Job Classification
- Balance
- Date Joined

Dataset Size:
- Number of Customers: 4,012
- Number of Features: 9

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook / Google Colab

---

# Project Workflow

## 1. Data Understanding

Performed initial data exploration:

- Dataset shape analysis
- Column information and data types
- Statistical summary
- Missing value analysis
- Feature overview

---

## 2. Data Cleaning

Performed data preprocessing:

- Converted `Date Joined` column into datetime format
- Checked missing values
- Validated numerical and categorical features
- Investigated data distributions

---

## 3. Feature Engineering

Created new analytical features:

### Age Group

Customers were categorized into different age groups:

- 18-24
- 25-44
- 45-59
- 60+

### Join Month

Extracted customer acquisition month from the registration date.

### Join Quarter

Created quarterly customer acquisition features.

---

# Exploratory Data Analysis (EDA)

The following analyses were performed:

## Customer Demographic Analysis

- Age distribution analysis
- Customer segmentation based on age groups
- Gender distribution across age categories

## Balance Analysis

Analyzed customer account balance patterns:

- Balance distribution
- Balance statistics
- Balance variation across age groups
- Balance comparison by job classification and region

## Regional Analysis

Analyzed customer distribution across UK regions:

- Customer count by region
- Regional customer concentration
- Balance patterns across regions

## Customer Acquisition Analysis

Analyzed customer joining trends:

- Monthly customer acquisition patterns
- Identification of higher and lower acquisition periods

---

# Key Insights

## Customer Distribution

- England represents the largest customer base, accounting for more than half of total customers.
- Scotland is the second-largest region by customer count.
- Customer distribution is not balanced across regions, indicating stronger market presence in England.

## Customer Balance Patterns

- Older customer groups generally show higher median account balances compared with younger groups.
- Balance values vary across different job classifications and regions.
- High-value customers exist across different demographic groups.

## Customer Acquisition Trends

- Customer acquisition patterns vary across different months.
- Higher customer acquisition levels were observed during specific periods of the year, which may indicate seasonal effects or marketing influences.

---

# Visualizations

## Customer Distribution by Region

![Customer Distribution](images/region_distribution.png)


## Customer Acquisition by Month

![Customer Acquisition](images/customer_acquisition_month.png)


## Balance Distribution by Age Group

![Balance by Age](images/age_balance.png)


## Balance by Job Classification and Region

![Balance Heatmap](images/heatmap_job_region.png)

---

# Project Structure
