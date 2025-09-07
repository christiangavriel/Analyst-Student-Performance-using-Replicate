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

AI Support Explanation: This analysis is supported by the IBM Granite Large Language Model (LLM), accessed through the Replicate API and integrated with LangChain. The model is used not only to provide automatic insights for each individual data row, such as assessing usefulness and generating clear explanations, but also to act as an intelligent assistant for data manipulation tasks. By creating a Pandas DataFrame agent, the model can rapidly execute operations like removing missing values, dropping duplicate records, and performing other routine preprocessing steps. In this way, the AI component helps accelerate both the exploratory and cleaning phases of the analysis, allowing the focus to shift toward interpreting results and identifying meaningful patterns in the dataset.
