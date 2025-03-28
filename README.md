# Student Performance and Learning Analysis 

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools used in this analysis](#tools-used-in-this-analysis)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

## Project Overview

This project aims to analyze student performance by examining various factors such as study hours, attendance rate, sleep patterns, and social media usage. By exploring correlations between these factors and academic performance (exam scores, assignment completion rates), we seek to uncover insights that can help students and educators improve learning outcomes.

## Data Source
The dataset used for this analysis contains student performance metrics, including:
- Demographics (Age, Gender, Student_ID  )
- Study Behavior (Study hours per week, online courses completed)
- Performance Metrics (Assignment completion rate, Attendance rate, Participation in Discussions)
- Lifestyle Factors (Time spent on social media per week, Use of Educational Tech )
- Academic performance (Grades, Exam score)
- Learning styles (Visual, Auditory, Kinesthetic, Reading/Writing)
- Self Care (Self_Reported_Stress_Level, Sleep hours per night )
  
The dataset was sourced from 
```
 (https://www.Kaggle.com).
```

## Tools used in this analysis
The Tools used in this analysis are as follows:
- Python (Programming Language)
- Pandas (Data manipulation)
- NumPy (Numerical computations)
- Matplotlib & Seaborn (Data visualization)
- Jupyter Notebook / VS Code (Development environment)

## Data Cleaning/Preparation 
The dataset was cleaned by:
- Removing missing or null values
- Removing duplicate columns 
- Replacing infinite values with appropriate values
- Standardizing column names for consistency
- Ensuring all numerical values were in the correct format

## Exploratory Data Analysis
EDA was performed to:
- Understand the distribution of numerical and categorical variables
- Identify outliers and anomalies
- Visualize correlations between variables
- Detect trends using histograms, barplots, piechart, group barchart and scatterplots

Key Visualizations:
- Correlation heatmap – Identified relationships between variables
- Distribution plots – Showed how exam scores varied with study hours and social media usage
- Preferred learning styles - visual, kinesthetic, Auditory, Reading/ writing
- Gender - Male, Female and other
- Preferred learning styles and exam scores 

## Data Analysis
Key Research Questions:
- How does study time impact student performance?
- How does use of tech impact student performance?
- Does social media usage negatively affect exam scores?
- Is there a correlation between sleep hours and academic success?
- Is there a correlation between sleep hours and Self-Reported Stress Level?
- How does attendance rate influence exam performance?
- How does learning styles impact student performance (Final grade)?

Methods Used:
- Correlation Analysis – To identify relationships between variables
- Descriptive Statistics – Mean, median, standard deviation of key metrics
- Data Visualizations – Heatmaps, bar charts, scatter plots, pie chart, group barchart

## Results/Findings
Key Findings:
- Study hours have a weak positive correlation with exam scores (but not as strong as expected).
- Learning style impact student performance.
- Sleep duration shows a weak but noticeable impact on student performance (Final grade).
- Attendance rate has a stronger impact on grades than online courses completed.
- Use of Tech impact online courses completed.
- Time spend on social impact student performance (Final grade).

## Recommendations
For Students:
- Increase study hours, but focus on quality over quantity.
- Reduce excessive social media use, especially before exams.
- Maintain a healthy sleep schedule to improve cognitive function.
- Prioritize class attendance to maximize learning.

For Educators:
- Encourage active participation in assignments and classes.
- Integrate digital learning tools for better engagement.
- Educate students on the impact of sleep and social media habits.

## Limitations
- The dataset is relatively small (only 8 observations), which limits generalization.
- The study does not account for external factors like personal motivation or teaching quality.
- Correlation does not imply causation—further studies are needed.

### References
```
 (https://www.Kaggle.com).
```
