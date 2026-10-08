# customer_behavior_analysis
Customer behavior analysis using Python, SQL &amp; Power BI to uncover purchasing patterns, customer insights, sales trends, and actionable business insights.
# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer preferences, and key business insights.

The project follows an end-to-end data analytics workflow, including **data loading, data cleaning, exploratory data analysis (EDA), SQL analysis using PostgreSQL, and interactive dashboard development in Power BI**.

The objective is to transform raw customer data into meaningful insights that can support data-driven business decisions.

---

## Dataset

The dataset contains customer shopping and transaction-related information, including:

* Customer demographics
* Product categories
* Purchase amounts
* Review ratings
* Payment methods
* Shopping frequency
* Discount usage
* Subscription information

The dataset was initially loaded and analyzed using Python.

---

## Tools & Technologies

* **Python** – Data loading, cleaning, and EDA
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **PostgreSQL** – Database management and SQL analysis
* **SQL** – Business and customer data analysis
* **Power BI** – Interactive dashboard and data visualization
* **Jupyter Notebook** – Python-based analysis environment

---

## Project Steps

### 1. Data Loading

* Imported the dataset into Python using Pandas.
* Examined the dataset structure and dimensions.
* Checked column names and data types.
* Identified missing values and duplicate records.

### 2. Exploratory Data Analysis

Performed EDA to understand:

* Customer purchasing patterns
* Product category performance
* Purchase amount distribution
* Review ratings
* Customer demographics
* Shopping frequency
* Payment preferences

### 3. Data Cleaning

The dataset was prepared for analysis by:

* Handling missing values
* Removing duplicate records where required
* Standardizing column names
* Correcting data types
* Checking data consistency
* Preparing clean data for database analysis

### 4. PostgreSQL & SQL Analysis

The cleaned dataset was loaded into a PostgreSQL database.

SQL queries were used to analyze:

* Customer behavior
* Product categories
* Purchase amounts
* Customer segments
* Ratings
* Shopping patterns
* Business performance

The analysis included filtering, aggregation, grouping, sorting, and other SQL operations to generate business-focused insights.

### 5. Power BI Dashboard

An interactive Power BI dashboard was created to visualize the key findings from the analysis.

The dashboard includes:

* Key Performance Indicators (KPIs)
* Customer analysis
* Category-wise analysis
* Purchase behavior
* Review rating insights
* Interactive filters and visualizations

---

## Dashboard

The Power BI dashboard provides an interactive overview of customer shopping behavior.

Users can explore different customer segments, product categories, purchasing patterns, and other key metrics using interactive visuals and filters.

### Dashboard Preview

*Add your Power BI dashboard screenshot here.*

```text
![Power BI Dashboard](images/dashboard.png)
```

---

## Results & Key Insights

The analysis helped identify important patterns in customer shopping behavior, including:

* Customer purchasing trends
* High-performing product categories
* Customer preferences
* Shopping frequency patterns
* Payment method preferences
* Review rating distribution
* Discount and subscription behavior

These insights can help businesses better understand their customers and make more informed decisions related to **sales, marketing, customer engagement, and product strategy**.

---

## Project Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## How to Run

### Python

1. Clone this repository.
2. Open the Jupyter Notebook.
3. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

4. Load the dataset.
5. Run the notebook cells sequentially to perform data cleaning and EDA.

### PostgreSQL

1. Install PostgreSQL.
2. Create a database.
3. Import the cleaned dataset into PostgreSQL.
4. Run the SQL queries from the `sql` folder.

### Power BI

1. Open the `.pbix` file in Power BI Desktop.
2. Update the data source if required.
3. Refresh the data.
4. Explore the interactive dashboard.

---

## Skills Demonstrated

* Python
* Pandas & NumPy
* Exploratory Data Analysis
* Data Cleaning
* SQL
* PostgreSQL
* Data Visualization
* Power BI
* Business Intelligence
* Data Analysis

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, transforming raw customer data into actionable insights using **Python, SQL, PostgreSQL, and Power BI**.

It showcases practical skills in data preparation, analysis, database querying, visualization, and business insight generation.
