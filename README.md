# Advanced-Stat-Computing-Proj
Advanced Statistical Computing final project
# Overview:
This project showcases expertise in data science through three comprehensive analyses, each focusing on different aspects of statistical computing and machine learning. The analyses demonstrate strong proficiency in exploratory data analysis (EDA), Monte Carlo simulations, and both supervised and unsupervised machine learning techniques.

# Project 1: Exploratory Data Analysis (EDA)
Utilizing various datasets, this part of the project emphasized extracting key insights and identifying data distributions through EDA. Four datasets with varying characteristics were analyzed, including:

Demographic and Workforce Dataset: Age and work hours were examined, with insights like a 40-hour mean workweek aligning with U.S. norms.
Abalone Biology Dataset: Relationships between dimensions and weights were visualized, revealing the linear contribution of diameter and height to abalone weight.
Ice Cream Sales and Temperature Dataset: Histograms and Q-Q plots demonstrated distribution consistency between variables, showing a linear correlation between temperature and sales.
New York Housing Market Dataset: Bedroom and bathroom distributions were mapped, illustrating linear relationships in house properties.

# Project 2: Monte Carlo Simulations and Data Partitioning
This section applied inferential statistics to the Forest Fires Dataset, using Monte Carlo methods to validate hypotheses:
Hypothesis Testing: Testing the mean temperature against a hypothesized population mean (20°C) revealed a significant deviation, confirmed through p-value analysis and critical value comparison.
Type I & II Error Assessment: Simulated critical values aligned closely with a 0.05 Type I error threshold, while power analysis showed decreasing power as the population mean approached the hypothesized mean.
Bootstrap Estimation: Resampling techniques estimated standard error and bias effectively, with Jackknife and Bootstrapping methods confirming the robustness of these estimates.
Cross-Validation: Linear, quadratic, and cubic models were evaluated, with the linear model achieving the lowest prediction error for temperature-humidity relationships.

# Project 3: Supervised and Unsupervised Learning
This section used the Water Potability Dataset for machine learning applications:
Supervised Learning with Classification Trees: Models with varying levels of complexity were trained to predict water potability. Model 4, which limited splits and used the Gini Index for splitting, achieved the best balance of accuracy and generalizability. Feature importance analysis identified pH, sulfate, and chloramines as the most influential variables.
Unsupervised Learning with Hierarchical Clustering: Agglomerative clustering with single, average, complete, and Ward’s linkage methods provided clustering insights. Average linkage, with the highest cophenetic correlation coefficient, was determined the best fit, offering insights into water quality segmentation.

# Conclusion:
This project demonstrates advanced data analysis and machine learning skills, particularly in using Monte Carlo simulations, resampling techniques, classification trees, and hierarchical clustering. The project highlights a robust approach to statistical analysis and data-driven decision-making through effective model selection, data partitioning, and feature engineering.

## The datasets are NOT mine and were obtained from Kaggle.
water portability: https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability 
adult income dataset: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset
