# WNS Analytics Wizard 2018
## Data Science  hackathon (Analytics Vidhya, Sept 14th -16th, 2018)

The Client is a large MNC and have 9 broad verticals across the organisation. One of the problem this client is facing is around
identifying the right people for promotion (only for manager position and below) and prepare them in time.

Currently the process, they are following is:

1. They first identify a set of employees based on recommendations/ past performance
2. Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required
   skill of each vertical
3. At the end of the program, based on various factors such as training performance, KPI completion (only employees with

For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their
new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the
entire promotion cycle.

Objective is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

## My Approach

I planned to use ensemble of SVC, Random forest, XGBoost. But found that result isn't good. So I just used XGBoost only 

## Result
 * Public Leaderboard - 0.4534336783
 * Private Leaderboard - 0.4745554874
