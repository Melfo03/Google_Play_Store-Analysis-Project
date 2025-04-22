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

#### Result

-**Differences Between Paid and Free Apps:** There is a clear distinction between paid and free apps. Free apps make up the majority of the total app count. On the other hand, paid apps are fewer in number, yet they hold a significant share in each genre category. Free apps generally offer more variety, while paid apps are more limited in number and tend to focus on specific categories.

-**Distribution by App Genres:** When analyzing the distribution of paid and free apps by genre, it is evident that the categories "Tools", "Entertainment", and "Education" are the most common genres for both types of apps. The "Medical" genre is quite prevalent in paid apps, but it is less represented in free apps. Furthermore, "Games" are highly dominant in free apps.

-**App Prices:** The average prices of paid apps show considerable variation. In certain categories, particularly in "Medical" and "Video Players & Editors", the price averages are notably higher. On the other hand, in some genres, the prices are either very low or free, often being released at zero or minimal cost.

-**Downloaded Apps:** When analyzing the number of installs by genre, the "Communication" genre has the highest number of installs. Additionally, genres like "Tools", "Entertainment", and "Education" also show significantly high download numbers.

**-Relationship Between Installs and Reviews:** A positive correlation is observed between the number of installs and the number of reviews. As the number of installs for an app increases, the number of reviews also tends to increase. This trend is typically seen for popular and widely downloaded apps. The trend line drawn to visualize this relationship confirms this correlation clearly. This suggests that as users download an app more frequently, they are more likely to leave feedback in the form of reviews.

   
 

