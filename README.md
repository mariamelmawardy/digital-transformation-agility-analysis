*Digital Transformation & Business Agility Analysis*
 Overview

This project analyzes the relationship between digital transformation and business agility using real survey data. The main objective is to measure how much digital transformation impacts business agility, not only to predict agility but also to compare different machine learning models and identify the most suitable one.

Dataset

The dataset is based on a structured survey with approximately 100 responses.

It consists of:

Digital Transformation (Q1–Q9)
Business Agility (Q10–Q18)

All responses are measured using a 5-point Likert scale (1–5).

 Data Preparation
Converted survey responses into numerical values
Created:
Digital Score = average of Q1–Q9
Agility Score = average of Q10–Q18

Demographics

To understand the sample characteristics, the following were analyzed:

Industry distribution
Experience level

These were visualized using pie charts to ensure the dataset represents diverse respondents.

 Methodology

The project uses supervised learning because:

Inputs (Digital Transformation factors) are known
Output (Agility Score) is defined

Models Used:

1. Linear Regression (Simple & Multiple)
Simple Linear Regression: Measures overall impact using Digital Score
Multiple Linear Regression: Analyzes the impact of each digital factor

3. Decision Tree
Captures non-linear relationships
Provides interpretable decision rules

4. Random Forest
Improves prediction accuracy
Reduces overfitting
Identifies important features

Model Evaluation

Models were evaluated using:

R² Score (for regression)
Accuracy and class metrics (for classification)

After comparison:

Simple Linear Regression achieved the highest R² score and was selected as the final model.

This indicates that the relationship between digital transformation and agility is relatively linear.

 Key Findings
There is a positive relationship between digital transformation and business agility
Digital transformation explains a significant portion of agility (based on R²)
Simpler models performed better due to the linear nature of the data

 Classification (Supporting Analysis)

Agility was categorized into:

Low Agility (1.00 – 2.33)
Moderate Agility (2.34 – 3.66)
High Agility (3.67 – 5.00)

Classification was used to:

Support regression findings
Evaluate how well agility levels can be distinguished

System Implementation

A simple system was developed where users can:

Input responses to all 18 survey questions
The system calculates:
Actual Agility Score (from Q10–Q18)
Predicted Agility Score (using the trained model on Q1–Q9)

 Output Example
 
Actual Agility: 3.22 (Moderate)
Predicted Agility: 3.54 (Moderate)
Insight:

The predicted value is higher than the actual value, indicating that digital transformation is not fully reflected in business agility.

ecommendations

The system generates recommendations based on low-scoring digital factors, such as:

Improve automation processes
Enhance digital leadership
Strengthen system integration
Improve data sharing

These recommendations help organizations translate digital capabilities into actual agility.

Conclusion

This project demonstrates that digital transformation has a measurable and positive impact on business agility. By combining data analysis with a practical system, the project not only identifies relationships but also provides actionable insights for improvement.

Future Work

Develop a user-friendly interface (web application)
Integrate real-time data input
Expand dataset for more accurate predictions


Predicts expected performance
Identifies gaps
Provides actionable recommendations
