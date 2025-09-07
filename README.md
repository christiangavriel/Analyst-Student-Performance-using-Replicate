Analysis Factors that Affecting Students Performance in Exams

This project analyzes the Student Performance dataset to identify key
demographic, educational, and behavioral factors influencing students
average exam scores. Using data cleaning, statistical methods, and
AI-assisted analysis, it reveals patterns and insights to help improve
student outcomes.

Dataset: \[StudentsPerformance.csv\] -
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data

Data Preparation: - Remove missing values (NA) - Remove duplicate
records - Add a new column `avg score` = average of math, reading, and
writing scores

Insights & Findings: - Student academic performance is shaped by both
individual preparation and family background.\
- Completing a test preparation course gives a consistent and
significant boost to scores across all student groups.\
- Higher levels of parental education correlate strongly with better
student outcomes.\
- A persistent performance gap remains among different ethnic groups,
even after accounting for test preparation.\
- These findings suggest that while individual effort and home
environment are key drivers, systemic factors also play a critical role
and require targeted interventions to ensure equitable success for all
students.

AI Support Explanation: This analysis is supported by IBM Granite LLM,
accessed via Replicate API and LangChain: - The model provides automatic
insights on each data row (usefulness, explanations) - It also assists
in creating a Pandas DataFrame agent to quickly manipulate data (drop
NA, drop duplicates)
