# Case-Study-Analyzing-Job-Market-Data-in-Power-BI

In this Power BI case study, we’ll explore a real-world job posting dataset to uncover insights for a fictional recruitment company called DataSearch. We’ll use Power Query to investigate and clean the data to find out what skills are most in-demand for data scientists, data analysts, and data engineers. We’ll then use DAX to build insightful visualizations of our findings. Finally, We’ll bring it all together using everything Power BI has to offer to create a business dashboard so that we can answer questions for the DataSearch team.

### Project Objectives
Investigate market trends for data science roles

* The context
An employee recruiting firm DataSearch,needs to uncover job trends
* Thetask
Discover trends in jobs and skills within the data science industry
* The dataset
Factitious collection of key details from job postings. The Dataset contains data about 25,114 job postings and 17 columns information about each job posting (Title, Date, Industry, Skills, ... )

### Data analysis Pipeline:
- 1. Checking Data
- 2. Exploring Data
- 3. Analyse and Visualise Data
- 4. Dashboarding
- 5. Communicating Insights

## Step 1: Exploratory Analysis
We'll start this Power BI case study by importing and cleaning the job posting dataset using Power Query. Once we’ve done this, it’s time to do some initial data exploration.

First, I imported and loaded the dataset into Power BI. Then, using Power Query tool, I 93% of values for Max and Min pay column were null values. This indicates that more than 90% of companies do not mention Maximum and Minimum of salary in their job postings. After than by sorting the Number of applicant column in a decending order, I understood that the most popular industries were Marketting and Adevrtisement, Computer Software, and Broadcast Media, respectively.

### More Experienced, Higher Level

Next, I want to obtain an idea of the relation between the Years of Experience and the Job Position level (e.g. Entry Level). To do so, I visualised the average Years of Experience and column and the Job Position Level column using a Treemap and a Bar chart.

![image](https://user-images.githubusercontent.com/113103161/206879491-99428656-0975-446a-ae6a-c0e13c05c677.png)

![image](https://user-images.githubusercontent.com/113103161/206880289-148148c7-bd3f-4c28-a751-5aecde2e6a21.png)


It is observed that the average experience years required for a Executive level job is around 15 years and you can land an Internship with less than a year experience.
At 15.17 years, Executive had the highest Average of Years of Experience and was 4,047.13% higher than Internship, which had the lowest Average of Years of Experience at 0.37 year. Moreover, across all 6 Job Position Levels, Average of Years of Experience ranged from 0.37 to 15.17 years.

### Job Posting Trend Analysis

Next, we are interested in observing the trend of job postings in time. So we visualise the Count of Job Posting IDs over Job Posting Date as time axis.

![image](https://user-images.githubusercontent.com/113103161/206880032-a93f49dd-92a1-4b6a-8eab-fb8257cf6d44.png)

It is evident that the first quarter of 2020 the number of job positions has been the lowest due to the rise of Covid-19. Between January 2017 and December 2021, Mid-Senior level had the largest increase in Count of Job Postings (174.48%) while Internship had the largest decrease (33.33%). The most recent Count of Job Postings anomaly was in September 2021, when Director had a low of 1. Count of Job Postings for Internship started trending up on February 2021, rising by 300.00% (3) in 4 months.

### Filtering for Data Related Job Titles

Now it's time to dig deeper into the dataset to gain info about data related jobs: Data Scientist, Data Analyst, Data Engineer, Machine Learning Engineer, and Data Science Manager. We start by analysing the number of job postings for each job title.  

![image](https://user-images.githubusercontent.com/113103161/206880551-48fd4ce7-b15e-4746-a93a-ffbd5cf3be5d.png)

At 3,462, Data Engineer had the highest Count of Job Postings and was 14,952.17% higher than Data Science Manager, which had the lowest Count of Job Postings at 23. Data Engineer accounted for 47.74% of Count of Job Postings. Across all 5 Job Titles, Count of Job Postings ranged from 23 to 3,462.

### Effect of Years Experience on Salary

In the next step of our EDA, we are interested in identifying influential factors on job market trend. One of the integral parts of a job is the compensation. Here, we analyse the effect of years of experience on each jab's offered salary.

## Step 2: Analyzing Market Trends

## Step 3: Building Dashboard
