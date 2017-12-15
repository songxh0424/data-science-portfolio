
# Table of Contents

1.  [Data Science Portfolio](#org068f61c)
    1.  [Past Projects](#org7ce489c)
    2.  [Frequently Used Packages](#orge0bd2e1)
    3.  [IDEs](#org6651bfa)


<a id="org068f61c"></a>

# Data Science Portfolio

This is a repository for some of my past projects in data science.


<a id="org7ce489c"></a>

## Past Projects

-   [Imbalanced Classification on Bankruptcy Prediction](http://rpubs.com/songxh0424/336831): This project employs several techniques, including SMOTE sampling and ROC curve, to tackle the inherent imbalance in bankruptcy data and builds machine learning models for bankruptcy prediction. Repeated cross-validation and alternative performance measures are used to evaluate models. Best models are selected based on cv ROC AUC values. The project is carried out using R, especially focusing on the usage of model training package `caret`. [Here](https://github.com/songxh0424/bankruptcy) is a link to the project repository.

-   [Analyzing Movie Scores on IMDb and Rotten Tomatoes](http://rpubs.com/songxh0424/336722): I love movies. I'm also intrigued by how movie websites rate movies and the fact that their ratings on the same movie can be vastly different. This project uses data visualization in `ggplot2` to demonstrate IMDb and RT's different behaviors in reviewing movies. I also made some top 10 lists of directors, actors or movies based movie ratings. Computational tools used in this project include SparkSQL, Python and R. [Here](https://github.com/songxh0424/projectA) is a link to the project repository.

-   [Overwatch Player Statistics and Hero Usage Analysis](http://rpubs.com/songxh0424/340988): Scraped data from the Overwatch career profile pages of 16,500 Overwatch players. Used data visualization to investigate the relationships between player performance, hero usage and skill rating. I also performed PCA and clustering analysis to categorize different types of players based on their hero usage patterns. [Link](https://github.com/songxh0424/Overwatch-Analysis) to the project repository.

-   [Injury Analysis for U of M Soccer Team](https://github.com/songxh0424/UMsoccer): I was in a multidisciplinary team of four U of M students. We were tasked by the university athletics department to analyze soccer team's training data and injury log. The objective is to find out correlations between training intensity and injury occurrence.


<a id="orge0bd2e1"></a>

## Frequently Used Packages

-   **R**
    -   `tidyverse`: A collection of packages that can tackle complex data manipulation, cleaning and visualization tasks, including `ggplot2` for plotting, `dplyr` and `tidyr` for data manipulation and cleaning, `lubridate` for handling date objects and `stringr` for string operations.
    -   `caret`: Stands for "Classification and Regression Training. A set of functions that streamline the entire process of model fitting. It covers most popular statistical models and machine learning techniques such as logistic regression, random forests, SVM, neural networks, and xgBoost.
-   **Python**
    -   `numpy`: Vectorization in Python.
    -   `pandas`: Introduces data series and data frames to Python. Makes working with data more pleasant in Python.
    -   `scikit-learn`: Machine learning library for Python. Just like `caret` in R, includes most tools in model fitting.


<a id="org6651bfa"></a>

## IDEs

-   **RStudio**: I used it when I first started to learn R. It has a great layout and the best R code completion I've seen. But eventually I ditched it for the flexibility and efficiency of Vim and the constant need to go into terminal.
-   **Vim + Tmux + Slime**: I used Vim for all my text file editing later on. Tmux can help me create custom layout and Slime plugin for Vim can send any code from Vim to a terminal/console. I used this combo for both R and Python. It works well with IPython and Pyspark as well.
-   **Spacemacs**: Spacemacs is a community-driven Emacs distribution that takes the advantages of Vim and Emacs. It can launch terminals, R and Python sessions all within the same screen. And all commands are just a few keystrokes away. Most of my data science work can be done in Spacemacs and I rarely need to go to another screen other than Chrome. On top of that, it has wonderful documentation both online and built-in.

My setup for the last two can be found [here](https://github.com/songxh0424/config).

