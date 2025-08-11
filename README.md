**mazon Clothing Sales Analysis**
This project performs a comprehensive Exploratory Data Analysis (EDA) on a dataset of Amazon clothing sales records. The goal is to uncover key business insights, understand customer behavior, and provide data-driven recommendations to a product and operations team.

**Project Objectives**
The primary objectives of this project were to:

Clean and Preprocess a real-world dataset, handling missing values, inconsistent data types, and outliers.

Conduct In-depth Analysis through univariate, bivariate, and multivariate exploration of sales, returns, customer demographics, and delivery performance.

Test Business Hypotheses to validate assumptions about customer behavior and sales performance.

Generate Actionable Insights with supporting visualizations to inform strategic decisions.

Create a Reproducible Project on GitHub, showcasing a structured approach to data analysis.

**Methodology**
The analysis followed a structured methodology, which is detailed in the accompanying Jupyter Notebook:

Initial Data Exploration: The dataset was loaded and an initial assessment was performed to understand its structure, data types, and potential quality issues.

Data Cleaning: Data quality issues such as missing values, inconsistent capitalization, and incorrect data types were addressed.

Feature Engineering: New features like order_month and discount_amount were created to facilitate deeper analysis.

Exploratory Data Analysis (EDA): A detailed EDA was conducted, including:

Univariate Analysis: Analyzing the distribution of individual variables.

Bivariate Analysis: Exploring relationships between pairs of variables.

Multivariate Analysis: Examining relationships among multiple variables to uncover complex patterns.

Hypothesis Testing: Statistical tests were used to formally test and validate a series of business-oriented hypotheses.

Insight Generation: Key findings were summarized into actionable business insights, each supported by a visualization and a recommendation.

**Key Findings & Insights**
Payment Method Influence: There is a significant difference in average order value (AOV) based on the payment method used, with credit card users having a higher AOV.

Delivery and Customer Satisfaction: The length of delivery time has a measurable impact on customer review ratings and return rates.

Discounts and Returns: Discounts are effective for increasing sales but do not have a strong correlation with reducing product returns.

Customer Segmentation: Different customer age groups show distinct purchasing patterns and preferences for specific product categories.

Regional Performance: Sales performance and delivery times vary by region, indicating potential logistical challenges in specific areas.

**Project Deliverables**
This repository contains the following:

EDA_Assignment.ipynb: The main Jupyter Notebook detailing the full data analysis process from start to finish, including cleaning, EDA, hypothesis testing, and visualizations.

README.md: This file, which provides an overview of the project.

requirements.txt: A list of all Python libraries and their versions required to run the notebook.

data/: A folder containing the raw dataset used for this project.

How to Reproduce the Project
To run this project on your local machine, follow these steps:

Clone the Repository:

Bash

git clone https://github.com/YourUsername/YourRepositoryName.git
cd YourRepositoryName
Set up the Environment: It is recommended to use a virtual environment.

Bash

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies:

Bash

pip install -r requirements.txt
Run the Notebook: Launch Jupyter Notebook and open EDA_Assignment.ipynb to view and run the code.

Bash

jupyter notebook
