Data Analysis Using Python

As a culminating project, we have a dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. My tasks include preprocessing the dataset, analyzing the data, and presenting my findings graphically.

Dataset used: https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link

Uploaded files : Jupyter notebook - Project.ipynb, Dataset - Project.csv

Below I will give an overview on what I have done in this project:

Step1: Imported the libraries - numpy, pandas, matplotlib.pyplot and seaborn

step2: Loaded the csv file Project.csv

step3: With the info() function on DataFrame, we were able to know that there are some null values present. In the Salary column, we filled the null values with the mean of the salary. In the Height feature, the data given is wrong, so we put some random heights in between 150 and 180 for all the rows.

step4: Calculated the team wise distribution of employees both in count and percentage. Successfully visualized it using a bar plot. We could find that the New Orleans Pelicans has the maximum number of employees present.

step5: Segregated employees based on the position within the company. Found out that position 'SG' has the maximum number of employee occupancy. Visualized it using the pie plot.

step6: Identified the predominant age group among the employees. Found out that most employees belong to the age-group 24. Visualized the same using pie plot.

step7: Tried to discover the teamand the position having high salary expenditure. Found out that Team Cleveland Cavaliers poses the overall salary consumption, also the position 'C' is getting the most salary. Visualized both of these using a bar plot.

step8: Investigated the correlation between Age and Salary and found that there is a slight positive correlation between Age and Salary. Visualized the correlation using seaborn graph.

This is the end of my Project!!! Tada !!!!


step7: Tried to discover the tean and the position having high salary expenditure. Found out that Team Cleveland Cavaliers posses the overall salary consumption, also the position 'C' is getting the most salary. Visualized both of these using bar plot.

step8: Investigated the correlation between Age and Salary and found that there is a slight positive correlation between Age and Salary. Visualized the correlation suing seaborn grapgh.

This is the end of my Project!!! Tada !!!!
