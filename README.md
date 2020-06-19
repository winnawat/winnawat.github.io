# Data Science Portfolio
#### Win Nawat Suvansinpan
Here is my work on various topics related to data science. Each project is its own repository which can be accessed via their respective links.  
[my github](https://github.com/winnawat)

## Predictive Models
### predicting bugfixtime
`linear regression` `decision tree` `random forest` `feature engineering` `NLP` `TF-IDF` `utility function`  
This project aims to predict the time taken to fix a bug given the information available when the bug was first filed, such as severity, bug description and project name. I started with 3 regression models and picked the best one based on accuracy score, the moedels' performance measured by a utility function, and the performance with constraints in a hypothetical situation.  
[github repository](https://github.com/winnawat/bugfixtime)  
[notebook](http://nbviewer.jupyter.org/github/winnawat/bugfixtime/blob/master/bugfixtime.ipynb)  

## Clustering Problems
### identifying hearthstone card packages
`k-means` `TSNE` `dimensionality reduction` `PCA` `data visualization`  
This project looks at a dataset of Hearthstone decks.

- The decks are clustered based on their card compositions. Clustering the decks highlights the subtle variants within an archetype.
- The cards are clustered based on the decks they are included in. Clustering the cards reveals which cards are usually included with each other, hence implying that they synergize well. This is called a 'package.' Knowing the packages in Hearthstone can help to highlight effective deckbuilding options. 

The clusters are also visualized using dimensionality reduction techniques.  
![Visualizing the clusters](https://github.com/winnawat/hearthstone-card-package/blob/master/cluster-partition.jpg)  
[github repository](https://github.com/winnawat/hearthstone-card-package)  
[notebook-analysis](http://nbviewer.jupyter.org/github/winnawat/hearthstone-card-package/blob/master/hs-package-kmeans.ipynb)  
[notebook-visualizations](http://nbviewer.jupyter.org/github/winnawat/hearthstone-card-package/blob/master/hs-package-viz.ipynb)

## Python Projects
### awsforyou
`AWS` `CI tools` `Git`  
This group project builds a tool that lets users estimate how long their machine learning projects will take to run on various AWS EC2 instances. This addresses the pain point where there are overwhelming options of EC2 instances available and one doesn't know which to pick. Runtime estimation is done by benchmarking the user's computation power against AWS EC2 instances. The relative rumtimes are then used to calculate the cost per instance and recommend the appropriate type of instance given time and budget.  
[github repository](https://github.com/winnawat/AWS-foryou)

### pwned passwords
`sensitive data` `exploratory data analysis` `large text files`  
This project explores the compromised password dataset without revealing a single password. The hypothesis is that vulnerable passwords are categorized into:

- passwords that are consecutive strokes on the keyboard ('123qweasdzxc' or 'qwertyui')
- passwords that are known to be vulnerable in a dictionary attack ('hello' or 'iloveyou')
- numeric passwords that are actually dates ('11072019' for November 7th 2019).

By generating the passwords in these categories and compare them to the dataset, we can visualize their proportions.  
[github repository](https://github.com/winnawat/pwned-pass-proj)  
[notebook](https://github.com/winnawat/pwned-pass-proj/blob/master/report-notebook/pwned-passwords-final-report.ipynb)

## Statistical Learning Concepts
### coding logistic regression from scratch
`logistic regression` `statistical learning` `gradient descent`  
This project puts the concept of logistic regression into code. Here, logistic regression with L2 regularization is coded from scratch and packaged into an importable module called `winlogistic`. The gradient descent process used here is fast gradient descent with backtracking on the step size.  
[github repository](https://github.com/winnawat/winlogistic)  
[notebook](https://github.com/winnawat/winlogistic/blob/master/polish-code-assignment.ipynb)
