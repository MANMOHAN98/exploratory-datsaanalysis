Exploratory Data Analysis - Titanic Dataset

 Task Objective

Perform EDA on the Titanic dataset to:

Understand the data using statistical summaries.

Visualize key patterns, trends, and relationships.

Draw insights useful for machine learning models.





Dataset

Name: Titanic - Machine Learning from Disaster

Source: Kaggle Dataset

Description: Contains details of passengers aboard the Titanic (e.g., age, class, sex, survival status).




 Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly (optional)





 Analysis Summary

1. Data Inspection

Loaded the dataset using Pandas.

Checked structure, data types, and null values.


2. Data Cleaning

Filled missing values in Age and Embarked.

Dropped the Cabin column due to too many missing values.


3. Descriptive Statistics

Generated summary statistics using .describe().

Analyzed distributions and central tendencies.


4. Visualizations

Histograms: Showed distribution of Age and Fare.

Boxplots: Identified outliers in Age and Fare.

Countplots: Compared survival by gender and class.

Heatmap: Visualized feature correlation.

Pairplot: Explored relationships among multiple features.


5. Key Insights

Women and children had higher survival rates.

Passengers in 1st class were more likely to survive.

Fare had some correlation with survival.

Most passengers were in 3rd class and male.




 Repository Contents

titanic.csv – Dataset file or link.

EDA_Titanic.ipynb – Jupyter Notebook with full analysis.

README.md – Project overview and details.
