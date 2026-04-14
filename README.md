# Digital Transformation & Business Agility Analysis

Overview

This project analyzes the relationship between digital transformation and business agility using real survey data. The goal is to understand how digital tools, systems, and practices affect an organization’s ability to respond quickly and effectively to changes.

🔹 Dataset

The dataset is based on a structured survey with 100 responses.
It includes two main sections:

Digital Transformation (9 questions)
Business Agility (9 questions)

All responses are measured using a 5-point Likert scale (1–5).

🔹 Methodology

The analysis was conducted using Python in Google Colab and includes:

Data cleaning and preprocessing
Conversion of responses into numerical values
Creation of:
Digital Transformation Score
Business Agility Score
Descriptive statistics
Correlation analysis
Simple linear regression
Multiple regression analysis
Feature importance analysis
Simulation (prediction of agility based on digital levels)
Data visualization (scatter plot and bar chart)

🔹 Key Findings

There is a clear positive relationship between digital transformation and business agility.
Simple regression shows that digital transformation explains about 64% of business agility (R² ≈ 0.64).
Multiple regression improves the model, explaining about 70% of business agility (R² ≈ 0.70).
The most impactful factors include:
Information sharing between departments
Access to updated business information
Use of digital systems in operations
Some factors showed weaker or negative impact, such as management support, likely due to indirect influence or similar responses across participants.
Simulation results confirm that increasing digital transformation leads to higher predicted business agility, making the results more practical and easier to interpret.

🔹 Tools Used

Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

🔹 Project Structure

data.ipynb → Main analysis notebook (run on Google Colab)
Dataset → Survey data used for analysis

🔹 Conclusion

The results show that digital transformation has a strong positive impact on business agility. Organizations that effectively use digital tools, especially for communication and access to information, are more likely to respond quickly to changes and improve performance. The project also demonstrates how data analysis and predictive models can support better and more informed business decision-making. 
