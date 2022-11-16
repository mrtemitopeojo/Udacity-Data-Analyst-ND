# Loan Data Exploration

This project dives into the loans given out to applicants as recorded by Prosper over a couple of years, it contains about 113,937 records of applicants, their current status (completed - defaulters), the creditscore of each applicant, borrowersAPR, state of residence of applicants, if applicants are existing houseowners, employment status, income range etc. This project focuses on trying to figure out issues around what are the possible causes of defaulters defaulting the payment. A slide giving a high level summary of this is presented also for better understanding.

## Dataset

The data set contains 113,937 of different loans and their uniue key for each loan. The data can be found via Kaggle [here](https://www.kaggle.com/datasets/shikhar07/prosper-loan-data)
the dataset was made up of 81 columns which were well documented in the link [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Code

I splitted the code into 2 major parts, Exploration and Explanatory. Data Exploration had the following subsections:

- Reading the data
- Data Wrangling
- Data Visualization 
  - Univariate Data Exploration
  - Bivariate Data Exploration
  - Multivariate Data Exploration 

For every question asked in this phase, I followed the "question - visualization - observation" framework.

The Explanatory code file majorly had just the important observations gotten from the exploratory phase, and cleaner visualizations. This was in turn converted into a slideshow that can be found embedded in the project, file name - "Data_Viz_Part2.slides". This might not be visible from Github as complaint of file size might occur, try cloning into a local repo and viewing directly on a browser.

### Dependencies/Libraries

Libraries used in this project include:

- pandas - for reading and exploring the dataset 
- numpy - allows for easy mathematical manipulations of dataset
- matplotlib - python plotting library to beautify visualizations
- seaborn - plotting library majorly for exploring visualizations as it does not have as much customizable features as matplotlib.
- %matplotlib inline - allows visualizations to be visible in notebook

## Summary of Findings

- Not all applicants are emloyed
- For defaulters, majority of the loan types given to them fall under the category of poorly rated loans, with only very few of them given highly rated loans.
- The major reason for loan collection by most of the applicants was for "Debt Consolidation" by a great amount, this might want to be looked at.
- "Professional" as an occupation had the highest number of defaulters.
- The distribution of amount loaned of applicants is right skewed because there are few applicants with high loan demand.
- Based on the ratio of deafuters to the ratio of loan recepients RD and SI states are the most likely to     default payment
- LoanStatus with "current" and "completed" have their own homes as at when they applied for loans
- Majority of the loan applicants income range are from 100k and greater with emloyed status



## Key Insights for Presentation

I want to look at the factors or features that had an effect on the amount loaned out. I also wanted to know the various people who were most likely to default a loan payment
For simplicity of the visualization I have looked at only few variables. The main dataframe was broken down into various data set through the projects for simplicity and for easy analysis
