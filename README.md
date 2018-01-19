
# Table of Contents

1.  [Data Science Portfolio](#orgc0edb81)
    1.  [Data Science Projects](#org0eef19a)
    2.  [Shiny Dashboards](#orgbd0a026)
    3.  [Frequently Used Packages](#org7cb5a2c)
    4.  [IDEs](#orgd7e2146)


<a id="orgc0edb81"></a>

# Data Science Portfolio

This is a repository for some of my past projects in data science.


<a id="org0eef19a"></a>

## Data Science Projects

-   [Imbalanced Classification on Bankruptcy Prediction](http://rpubs.com/songxh0424/336831): This project employs several techniques, including SMOTE sampling and ROC curve, to tackle the inherent imbalance in bankruptcy data and builds machine learning models for bankruptcy prediction. Repeated cross-validation and alternative performance measures are used to evaluate models. Best models are selected based on cv ROC AUC values. The project is carried out using R, especially focusing on the usage of model training package `caret`. [Here](https://github.com/songxh0424/bankruptcy) is a link to the project repository.

-   [Deep Dive into Airbnb Listing Data:](https://rpubs.com/songxh0424/341895) This is the product of an one-day datathon hosted by Citadel LLC. We had seven hours to come up with a data analysis report using [Airbnb listing data](http://insideairbnb.com/get-the-data.html). We ended up being the third place out of 24 teams. Our report delves into aspects from investigating the relationships between keywords in listing names and listing price, to using machine learning techniques to predict listing price based on the housing condition.

-   [Analyzing Movie Scores on IMDb and Rotten Tomatoes](http://rpubs.com/songxh0424/336722): I love movies. I'm also intrigued by how movie websites rate movies and the fact that their ratings on the same movie can be vastly different. This project uses data visualization in `ggplot2` to demonstrate IMDb and RT's different behaviors in reviewing movies. I also made some top 10 lists of directors, actors or movies based movie ratings. Computational tools used in this project include SparkSQL, Python and R. [Here](https://github.com/songxh0424/projectA) is a link to the project repository.

-   [Overwatch Player Statistics and Hero Usage Analysis](http://rpubs.com/songxh0424/340988): Scraped data from the Overwatch career profile pages of 16,500 Overwatch players. Used data visualization to investigate the relationships between player performance, hero usage and skill rating. I also performed PCA and clustering analysis to categorize different types of players based on their hero usage patterns. [Link](https://github.com/songxh0424/Overwatch-Analysis) to the project repository.

-   [Injury Analysis for U of M Soccer Team](https://github.com/songxh0424/UMsoccer): I was in a multidisciplinary team of four U of M students. We were tasked by the university athletics department to analyze soccer team's training data and injury log. The objective is to find out correlations between training intensity and injury occurrence.


<a id="orgbd0a026"></a>

## Shiny Dashboards

These are Shiny web apps I created for some of my projects. The web pages can take some time to load as the underlying data manipulation and plotting can be complex sometimes.

-   [MovieStats: An interactive web app to learn insights from movie ratings](https://songxh.shinyapps.io/movies-dashboard/): This is an interative web application I created using [R Shiny](https://shiny.rstudio.com/). Data comes from [MovieLens Latest Datasets](https://grouplens.org/datasets/movielens/latest/), [OMDb API](http://www.omdbapi.com/), and information scraped from IMDb. The goal is to provide a visually compelling tool to deliver insights into movie ratings, box office, as well as analytics for individual actors and directors. The app also features some interesting movie facts hidden with data. The interactive data visualizations in this app are built with [Plotly](https://plot.ly/).

-   [Low-value Imaging Measures Specification](https://songxh.shinyapps.io/mprove-dashboard/): A dashboard I created during my internship at the University of Michigan Health System. The purpose of this dashboard is to display information of the measures we used to identify low-value imagings. It contains both high level descriptions of measures and detailed tables of ICD codes used in the measures. The ICD-10 tables are currently faulty due to ongoing development of the underlying R package that I wrote for the project.


<a id="org7cb5a2c"></a>

## Frequently Used Packages

-   **R**
    -   `tidyverse`: A collection of packages that can tackle complex data manipulation, cleaning and visualization tasks, including `ggplot2` for plotting, `dplyr` and `tidyr` for data manipulation and cleaning, `lubridate` for handling date objects and `stringr` for string operations.
    -   `caret`: Stands for "Classification and Regression Training. A set of functions that streamline the entire process of model fitting. It covers most popular statistical models and machine learning techniques such as logistic regression, random forests, SVM, neural networks, and xgBoost.
    -   `rvest`: A great package that enables powerful and flexible web scraping in R.
    -   `shinydashboard`: All my shiny apps are built around this package. The package includes functions that make creating organized and appealing layouts a very easy and pleasant experience.
-   **Python**
    -   `numpy`: Vectorization in Python.
    -   `pandas`: Introduces data series and data frames to Python. Makes working with data more pleasant in Python.
    -   `scikit-learn`: Machine learning library for Python. Just like `caret` in R, includes most tools in model fitting.


<a id="orgd7e2146"></a>

## IDEs

-   **RStudio**: I used it when I first started to learn R. It has a great layout and the best R code completion I've seen. But eventually I ditched it for the flexibility and efficiency of Vim and the constant need to go into terminal.
-   **Vim + Tmux + Slime**: I used Vim for all my text file editing later on. Tmux can help me create custom layout and Slime plugin for Vim can send any code from Vim to a terminal/console. I used this combo for both R and Python. It works well with IPython and Pyspark as well.
-   **Spacemacs**: Spacemacs is a community-driven Emacs distribution that takes the advantages of Vim and Emacs. It can launch terminals, R and Python sessions all within the same screen. And all commands are just a few key strokes away. Most of my data science work can be done in Spacemacs and I rarely need to go to another screen other than Chrome. On top of that, it has wonderful documentation both online and built-in.

My setup for the last two can be found [here](https://github.com/songxh0424/config).

