## Data Scientist Salary Prediction

![Data Scientist Salary Prediction](https://github.com/user-attachments/assets/5eeaafd3-ad50-4908-8262-477f7281e74c)

## Objective

Analytics India Annual Salary Study which aims to understand a wide range of trends data science says that the median analytics salary in India for the year 2017 is INR 12.7 Lakhs across all experience level and skill sets. So given the job description and other key information can you predict the range of salary of the job posting? What kind of factors influence the salary of a data scientist? The study also says that in the world of analytics, Mumbai is the highest paymaster at almost 13.3 Lakhs per annum, followed by Bengaluru at 12.5 Lakhs. The industry of the data scientist can also influence the salary. Telecom industry pays the highest median salaries to its analytics professionals at 18.6 Lakhs. What are you waiting for, solve the problem by predicting how much a data scientist or analytics professional will be paid by analysing the data given in this hackathon.

## Data Collection

I have sourced the dataset from "Machine Hack Gen AI" website.

https://machinehack.com/hackathons/predict_the_data_scientists_salary_in_india_hackathon/data

This dataset contains salary range of 18,406 Data Scientists of india.

## Challanges

- Only 6 variables are present to predict the salary range
- 3 of them are text type data with multiple lines of text.
- 1 of the variable had 78% of Missing values.

## Data Preprocessing

- Removed duplicate records.
- Extracted numbers from object variable.
- Did Token Normalization to standardize the data.
- With the help of TfidfVectorizer, converted the text data into numerical data.

## Key variables

- Minimum and Maximum experiance.
- Surprisingly, Missing Values had a strong relation while predicting the salary.
- Location.
- Job description.

## Learnings

- Learned how to deal with text Data.
- Converting Multi-class classification problem into Regression.
- Bucketing the values to reduce Dimensionality.
