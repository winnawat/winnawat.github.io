# Data Science Portfolio
#### Win Nawat Suvansinpan
Listed here are my work on various topics related to data science. Each project is its own repository which can be accessed via their respective links.

## Predictive Models
### predicting bugfixtime
`linear regression` `decision tree` `random forest` `feature engineering` `NLP` `TF-IDF` `utility function`  
This project aims to predict the time taken to fix a bug given the information available when the bug was first filed such as severity, bug description and project name. I started with 3 regression models and picked the best one based on accuracy score, the moedels' performance measured by a utility function, and the performance with hypothetical constraints in a hypothetical situation.  
[github repository](https://github.com/winnawat/bugfixtime)  
[notebook](http://nbviewer.jupyter.org/github/winnawat/bugfixtime/blob/master/bugfixtime.ipynb)  

## Clustering Problems
### identifying hearthstone card packages
`k-means` `TSNE` `dimensionality reduction` `PCA` `data visualization`  
This project looks at a dataset of Hearthstone decks and attempts to cluster 1) the decks based on their compositions, and 2) the cards based on the decks they are included in. Clusterings the decks highlights the subtle variants within an archetype. Clustering the cards reveals what cards are usually included with each other and hence implying that they synergize well. This is called a 'package.' Knowing the packages in Hearthstone can help to highlight effective deckbuilding options.  
[github repository](https://github.com/winnawat/hearthstone-card-package)  
[notebook-analysis](http://nbviewer.jupyter.org/github/winnawat/hearthstone-card-package/blob/master/hs-package-kmeans.ipynb)  
[notebook-visualizations](http://nbviewer.jupyter.org/github/winnawat/hearthstone-card-package/blob/master/hs-package-viz.ipynb)

## Python Projects
### awsforyou
`AWS` `CI tools` `Git`  
This group project builds a tool that lets users estimate how long their machine learning projects will take to run on various AWS EC2 instances. This addresses the pain point where there are overwhelming options of EC2 instances available and one is usually unsure which to pick. Runtime estimation is done by benchmarking the user's computation power against AWS EC2 instances. The relative rumtimes are then used to calculate the cost for each instance and arrive at a recommendation for the appropriate type of instance given time and budget.  
[github repository](https://github.com/winnawat/AWS-foryou)

### pwned passwords
`sensitive data` `exploratory data analysis` `large text files`  
This project explores the compromised password dataset without actually revealing any password. The project attempts to explore the different types of passwords that are commonly used and visualize their proportions. Passwords are categorized into the following types, passwords that are consecutive strokes on the keyboard ('123qweasdzxc' or 'qwertyui'), passwords that are known to be vulnerable in a dictionary attack ('hello' or 'iloveyou') and numeric passwords that are actually dates ('11072019' for November 7th 2019).  
[github repository](https://github.com/winnawat/pwned-pass-proj)  
[notebook](https://github.com/winnawat/pwned-pass-proj/blob/master/report-notebook/pwned-passwords-final-report.ipynb)

## Implementing Statistical Learning
### Coding Logistic Regression From Scratch
`logistic regression` `statistical learning` `gradient descent`  
This project puts the concept of logistic regression into code. Here, logistic regression with L2 regularization is coded from scratch and packaged into an importable module called `winlogistic`. The gradient descent process used here is fast gradient descent with backtracking on the step size.  
[github repository](https://github.com/winnawat/winlogistic)  
[notebook](https://github.com/winnawat/winlogistic/blob/master/polish-code-assignment.ipynb)
