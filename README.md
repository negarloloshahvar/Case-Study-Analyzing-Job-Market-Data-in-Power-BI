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

Next, I want to obtain an idea of the relation between the Years of Experience and the Job Position level (e.g. Entry Level). To do so, I visualised the average Years of Experience and column and the Job Position Level column using a Treemap and a Bar chart.

![image](https://user-images.githubusercontent.com/113103161/206879491-99428656-0975-446a-ae6a-c0e13c05c677.png)


![image](https://user-images.githubusercontent.com/113103161/206877061-f52442d4-36dd-4679-997f-cd5001100450.png)


It is observed that the average experience years required for a Executive level job is around 15 years and you can land an Internship with less than a year experience.

Next, we are interested in observing the trend of job postings in time. So we visualise the Count of Job Posting IDs over Job Posting Date as time axis.

![image](https://user-images.githubusercontent.com/113103161/206879546-cc2d9016-5ea9-434f-ad34-fa48cdde3cab.png)

It is evident that the first quarter of 2020 the number of job positions has been the lowest due to the rise of Covid-19.


## Step 2: Analyzing Market Trends

## Step 3: Building Dashboard
