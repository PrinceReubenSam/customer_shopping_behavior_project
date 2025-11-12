# Customer Shopping Behavior Analysis

## Project Overview

This project is an end-to-end data analysis of a retail dataset to understand customer shopping behavior and drive strategic business decisions. The study uncovers insights on spending patterns, top-selling products, customer segmentation, and the impact of subscriptions. The final output includes an interactive Power BI dashboard and a formal report with actionable recommendations to enhance marketing strategies and optimize operations.

## Dataset

The dataset, `customer_shopping_behavior.csv`, contains 3,900 transactional records with 18 distinct features, including:
-   **Customer Demographics:** Age, Gender, Location
-   **Purchase Details:** Item Purchased, Category, Purchase Amount ($), Season
-   **Behavioral Metrics:** Previous Purchases, Review Rating, Subscription Status, Shipping Type, Discount Applied

## Tools and Technologies

-   **Data Preparation & Analysis:** Python (Pandas, Jupyter Notebook)
-   **Database Management & Querying:** PostgreSQL
-   **Data Visualization & Dashboarding:** Power BI
-   **Reporting & Presentation:** Gamma, PDF

## Project Workflow & Steps

1.  **Data Preparation (Python):**
    -   Loaded the dataset using Pandas.
    -   Conducted Exploratory Data Analysis (EDA) to understand data distributions and identify initial patterns.
    -   Cleaned the data by handling missing values in the `Review Rating` column, standardizing column names to a consistent format (snake_case), and removing redundant columns.
    *File: `02_customer_shopping_behaviour_data_cleaning_python.ipynb`*

2.  **Advanced Analysis (SQL):**
    -   Loaded the cleaned dataset into a PostgreSQL database.
    -   Executed complex SQL queries to perform deeper analysis, such as calculating revenue by gender, identifying high-spending discount users, and comparing subscriber vs. non-subscriber revenue.
    *File: `03_customer_shopping_behaviour_eda_sql.sql`*

3.  **Dashboard Creation (Power BI):**
    -   Connected Power BI to the PostgreSQL database.
    -   Developed an interactive dashboard to visualize key metrics, including top products, revenue by age group, and the impact of discounts and shipping types.
    *File: `04_customer_shopping_behaviour_dashboard.pbix`*

4.  **Reporting & Presentation:**
    -   Summarized the key findings and insights into a comprehensive PDF report.
    -   Created a final presentation using Gamma to communicate the results and business recommendations to stakeholders.
    *Files: `05_Customer Shopping Analysis Report.pdf` and the provided Gamma presentation.*

## Interactive Dashboard

The Power BI dashboard provides a dynamic view of the key performance indicators (KPIs) and analytical findings. It allows users to filter data by categories, demographics, and seasons to explore insights interactively.

*(You can add a screenshot of your Power BI dashboard here)*
`![Dashboard Screenshot](link_to_your_dashboard_image.png)`

**Key Visualizations Include:**
-   Total Revenue by Gender and Age Group
-   Top 5 Products by Customer Rating
-   Impact of Subscriptions on Total Revenue
-   Analysis of Discount Usage Across Different Product Categories

## Key Results & Business Recommendations

The analysis yielded several actionable insights that led to the following strategic recommendations:

1.  **Focus on Clothing:** Prioritize promotions and inventory for the "Clothing" category, as it is the highest revenue generator.
2.  **Boost Subscriptions:** Launch campaigns to improve the current 27% subscription rate by highlighting exclusive benefits and offers.
3.  **Enhance Customer Loyalty:** Develop a rewards program to retain the 3,116 "Loyal" customers who have made more than 10 purchases.
4.  **Implement Targeted Advertising:** Promote top-rated products to the "Middle Aged" demographic, which is the highest-spending age group ($88,833 in revenue).

## How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```
2.  **Dataset:** The raw data is available in `01_customer_shopping_behavior.csv`.
3.  **Python Analysis:** Open `02_...ipynb` in a Jupyter Notebook environment to see the data cleaning and preparation steps.
4.  **SQL Queries:** Use the `03_...sql` script in a PostgreSQL client after loading the cleaned data.
5.  **Dashboard:** Open `04_...pbix` with Power BI Desktop to interact with the dashboard.
6.  **Final Report:** Review the complete analysis and recommendations in `05_...pdf`.

## Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/reuben-samuel-b55b97234/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/reubensamuel/Reuben-Samuel-Data-Analyst-Portfolio-26495394acfe4805dbd8af2158d647aad)
