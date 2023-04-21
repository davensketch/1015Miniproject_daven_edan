# 1015Miniproject_daven_edan
# Team Members

# About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on analysing the [world happiness index](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2022) from the world report index.
# Problem Definition and Explanation
The quest for happiness has evolved into a crucial component of both personal and social well-being in today's environment of fast change. We may learn a lot about the aspects that lead to a fulfilled and content populace by examining the factors that influence happiness in a nation. We can pinpoint important factors influencing happiness and spot trends and patterns that might have a big influence on total life satisfaction by analyzing a large dataset that includes numerous social, economic, and political variables. Understanding these characteristics enables us, organizations, and people to create and implement focused initiatives that can improve citizens' well-being, advance a more peaceful society, and ultimately develop a happier country.

# Objective
Our objective is to utilize machine learning techniques, specifically Random Forest and Hierarchical Clustering, to investigate factors affecting happiness in a country. Random Forest offers robustness and accuracy in modeling complex relationships, while Hierarchical Clustering reveals regional patterns by grouping countries based on similarity. Together, these methods provide valuable insights to drive targeted strategies for enhancing well-being across diverse nations and cultures.

# What we have provided 
1. Data set for World Happiness
2. Presentation Slides
3. Our main project Notebook

   --> Data Cleaning and Preperation
   
   --> EDA ( Exploratory Data Analysis)
   
   --> Machine Learning Models ( Explained Below )

# Models Used
For this project we used two different Machine Learning (ML) to help us with our project, these two are:
  1. Random Forest 
  2. Hierarchical Clustering

# The flow of our project

## Data Cleaning
* Firstly we checked if all values in the data set are real and valid ( no NaN values )
* Next we also checked for the presence of duplicate rows which may introduce bias


## Exploratory Data Analysis
* In the data set which we used, there was 12 different headers, factors affecting happiness in a country
* We Explored the features of each categorical fata to analyse any patterns and outliers
* We then used a heat map to visualise their correlation, removing headers such as "Rank" which does not play a part
* We used Bar Charts to also aid in visualsing the ranking of countries happiness with factors such as Dystopia
* Also showed an alternate view on relation of life expectancy with Country Happiness

## Machine Learning
* We scaled the variables to ensure that it would work well with our Machine Learning Algorithms
1. Random Forest
* Because of its capabilities and traits, Random Forest is particularly helpful in machine learning for categorical data. Random Forest, a supervised learning method, is adaptable for categorical target variables since it can handle both classification and regression issues. It uses an ensemble technique, which reduces overfitting and improves accuracy by combining predictions from many decision trees. In comparison to a single decision tree model, this method accurately captures the complex connections in categorical data and yields more accurate predictions. As a result, Random Forest has gained popularity as a solution for machine learning problems requiring categorical data.

2. Hierarchical Clustering
* For categorical data in machine learning, the use of hierarchical clustering is significant for a number of reasons. Its capacity to accommodate multiple data types, including both category and numeric variables, is a significant benefit. This approach can handle datasets with a variety of data formats by using the right distance measures, such Gower's distance. Furthermore, hierarchical clustering offers thorough details on the similarity between observations, making it possible to identify data points that are closely connected. There are few other clustering techniques that offer this level of specificity. This approach is more reliable and adaptable for evaluating categorical data in varied situations because it is less subject to starting circumstances, outliers, and assumptions about cluster form.



# Conclusion
1. We have concluded that most factors (GDP, Social Support, etx...) are important and cannont be removed, besides Whisker High and Low, Rank and Country as they cannot be used as predictor variables.
2. The Bar chart for Random Forest shows conclusion of Tree created. suggesting that GDP per capita has the highest importance in influencing happiness in a country.
3. The more developed the country, (better social support, stronger economies) would tend to have a higher happiness score compared to underdeveloped countries.

# References
* https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2022
* https://www.datacamp.com/tutorial/random-forests-classifier-python
* https://crunchingthedata.com/when-to-use-hierarchical-clustering/#:~:text=Another%20advantage%20of%20hierarchical%20clustering%20is%20that%20it%20can%20be,types%20such%20as%20Grower's%20distance.


