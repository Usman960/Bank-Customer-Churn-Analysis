# Bank-Customer-Churn-Analysis

**Note:** Please use **Excel 365** to explore this project to ensure all the formulae used in this project are availabe.

Dataset size: 10k rows, 12 columns

Link to the dataset: https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset

Summary of my findings:

### Data Acquisition:
Downloaded the dataset from **Kaggle**

### Data Preprocessing:
1. Ensured that no duplicates or missing values were overlooked by meticulously inspecting all columns.
2. Standardized the format of balance and estimated_salary to currency.

### Data Analysis:
1. Conducted hypothesis testing to compare churned and non-churned customers across various attributes.
2. Utilized histograms to examine skewness in the age, credit score, and balance columns, leading to the creation of relevant categories.
3. Employed pivot tables to simultaneously analyze multiple attributes, facilitating the discovery of additional insights.

### Data Visualization:
Developed a dynamic dashboard featuring pivot slicers, enabling seamless filtering of multiple attributes for interactive data exploration.

### Insights:
1.	Customers aged 42 and above exhibited the highest churn rate among all age groups.
2.	Non-active members were found to churn nearly twice as much as active members.
3.	Customers utilizing exactly two products displayed the lowest churn rate, followed by those using only one product.
4.	Customers using three to four products experienced a churn rate exceeding 50%.

### Conclusions:
1.	Cease promoting three to four products to each customer, as it leads to higher churn rates.
2.	Conduct a comprehensive survey among all customers to prioritize their product preferences based on individual needs.
3.	For customers aged 42 and above, promote the top two ranked products identified by the survey.
4.	For other customers, tailor promotions based on their preferences, limiting the offering to one or two products.
5.	Implement targeted campaigns to re-engage non-active members, leveraging the insights gained from the survey.

