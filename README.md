# Data Science Portfolio
#### Win Nawat Suvansinpan
Listed here are my work on various topics related to data science. Each project is its own repository which can be accessed via their respective links.

## Predictive Models
### predicting bugfixtime
`linear regression` `decision tree` `random forest` `feature engineering` `NLP` `TF-IDF` `utility function`  
This project aims to predict the time taken to fix a bug given the information available when the bug was first filed such as severity, bug description and project name. I started with 3 regression models and pick the best one based on accuracy score, the moedels' performance measured by a utility function, and the performance with hypothetical constraints.

## Clustering Problems
### identifying hearthstone card packages
`k-means` `TSNE` `dimensionality reduction` `PCA` `data visualization`  
This project looks at a dataset of Hearthstone decks and attempt to cluster 1) the decks using their compositions, and 2) the cards using the decks they are included in. CLustering the cards reveal what cards are usually included with each other and hence implying that they synergize well. This is called a 'package' and knowing the packages in Hearthstone can help to highlight good deckbuilding options.

## Python Projects
### awsforyou
`AWS` `CI tools` `Git`  
This group project builds a tool that lets users estimate how long their machine learning projects will take to run on various AWS EC2 instances. This is done by benchmarking the user's computation power against AWS EC2 instances. The relative rumtimes are then used to calculate the cost for each instance and arrive at a recommendation for the appropriate type of instance given time and budget.

### pwned passwords
`sensitive data` `exploratory data analysis` `large text files`  
This project explores the compromised password dataset without actually revealing any password. The project attempts to explore the different types of passwords that are commonly used and visualize their proportions. For example, passwords that are consecutive strokes on the keyboard ('123qweasdzxc' or 'qwertyui'), passwords that are known to be vulnerable in a dictionary attack ('hello' or 'iloveyou') and passwords that are actually dates ('11072019' for November 7th 2019).

## Implementing Statistical Learning
### Coding Logistic Regression From Scratch
`logistic regression` `statistical learning` `gradient descent`  
This project puts the concept of logistic regression into code. Here, logistic regression with L2 regularization is coded from scratch and packaged into a module called `winlogistic`. The gradient descent process used here is fast gradient descent with backtracking on the step size.

