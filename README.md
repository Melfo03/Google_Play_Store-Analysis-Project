# Google Play Store Analysis Project

### Project Overview
---
Analyzing and pre processing Google Play Store dataset to gain insights into app ratings, reviews, and category performance.


### Data Source

The dataset we use for analysis is "googleplaystore.csv".In this dataset each app has values for category, rating, size, and more.

- [Dataset's kaggle page](https://www.kaggle.com/datasets/lava18/google-play-store-apps)


### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.


### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- What is the mean of installs by genres?
- Are there any correlations between the variables?


### Results/Findings

#### Descriptive Statistics

![Descriptive Statistics Summary](images/Descriptive_Statistics_Summary.png)

#### Correlations
Upon analyzing the cleaned dataset, as seen in the image below, the only notable correlation is the moderately strong positive correlation between 'Reviews' and 'Installs'.

![a](images/correlation_matrix.png)

#### Trend Line
![c](images/Trend_Line_Between_Installs_and_Reviews.png)

#### Findings
 - According to the chart below, the genre with the most apps is 'Tools'
   
   ![b](images/Apps_Count_by_Genre.png)

   
 - According to the chart below, the genre with the most paid apps is 'Medical
 
   ![c](images/Paid_Apps_Count_by_Genre.png)

 - According to the chart below, the genre with the highest average price is 'Medical'

   ![c](images/Average_Price_of_Paid_Apps_by_Genre.png)


 - According to the chart below, the genre with the highest average number of installs is 'Communication'

   ![c](images/Downloads_Count_by_Genre.png)
   

  - According to the chart below, the content rating with the most apps by far is 'Everyone'

    ![c](images/Content_Rating_Distribution.png)
   

  - According to the pie chart below, the content rating with the most downloads by far is 'Everyone'

    ![c](images/Installs_By_Content_Rating.png)


  - According to the chart below, by far, the number of free apps is higher

    ![c](images/Count_of_Paid_vs_Free_Apps.png)

   
 

