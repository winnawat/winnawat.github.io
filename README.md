# Data Science Portfolio
#### Win Nawat Suvansinpan
Here is my work on various topics related to data science. Each project is its own repository which can be accessed via their respective links.  
[my github](https://github.com/winnawat)

## Predictive Models
### predicting bugfixtime
`python` `linear regression` `decision tree` `random forest` `feature engineering` `NLP` `TF-IDF` `utility function`  
This project aims to predict the time taken to fix a bug given the information available when the bug was first filed, such as severity, bug description and project name. I started with 3 regression models and picked the best one based on accuracy score, the moedels' performance measured by a utility function, and the performance with constraints in a hypothetical situation.  
[github repository](https://github.com/winnawat/bugfixtime)  
[notebook](http://nbviewer.jupyter.org/github/winnawat/bugfixtime/blob/master/bugfixtime.ipynb)  

## Statistics
### using statistics to determine if one team is better than the other in a competitive sports match.
`R` `statistics` `experiment design` `hypothesis testing` `binomial distribution` `probability`
This project sprouted from curiosity. Watching the 2020 Olympic games in Tokyo got me wondering if the rules of competitive sports have too much room for luck. That is, runner ups are actually as good as other competitors, just less lucky. By framing the problem this way, we can use statistics to help us comprehend and hopefully reduce uncertainty. At least on paper.
[github repository](https://github.com/winnawat/may-the-best-team-win)  
[notebook](https://github.com/winnawat/may-the-best-team-win/blob/main/case_badminton.pdf)  

## Clustering Problems
### identifying hearthstone card packages
`python` `k-means` `TSNE` `dimensionality reduction` `PCA` `data visualization`  
This project looks at a dataset of Hearthstone decks.

- The decks are clustered based on their card compositions. Clustering the decks highlights the subtle variants within an archetype.
- The cards are clustered based on the decks they are included in. Clustering the cards reveals which cards are usually included with each other, hence implying that they synergize well. This is called a 'package.' Knowing the packages in Hearthstone can help to highlight effective deckbuilding options. 

The clusters are also visualized using dimensionality reduction techniques.    
[github repository](https://github.com/winnawat/hearthstone-card-package)  
[notebook-analysis](http://nbviewer.jupyter.org/github/winnawat/hearthstone-card-package/blob/master/hs-package-kmeans.ipynb)  
[notebook-visualizations](http://nbviewer.jupyter.org/github/winnawat/hearthstone-card-package/blob/master/hs-package-viz.ipynb)

## Python Projects
### awsforyou
`python` `AWS` `CI tools` `Git`  
This group project builds a tool that lets users estimate how long their machine learning projects will take to run on various AWS EC2 instances. This addresses the pain point where there are overwhelming options of EC2 instances available and one doesn't know which to pick. Runtime estimation is done by benchmarking the user's computation power against AWS EC2 instances. The relative rumtimes are then used to calculate the cost per instance and recommend the appropriate type of instance given time and budget.  
[github repository](https://github.com/winnawat/AWS-foryou)

### pwned passwords
`python` `sensitive data` `exploratory data analysis` `large text files`  
This project explores the compromised password dataset without revealing a single password. The hypothesis is that vulnerable passwords are categorized into:

- passwords that are consecutive strokes on the keyboard ('123qweasdzxc' or 'qwertyui')
- passwords that are known to be vulnerable in a dictionary attack ('hello' or 'iloveyou')
- numeric passwords that are actually dates ('11072019' for November 7th 2019).

By generating the passwords in these categories and compare them to the dataset, we can visualize their proportions.  
[github repository](https://github.com/winnawat/pwned-pass-proj)  
[notebook](https://github.com/winnawat/pwned-pass-proj/blob/master/report-notebook/pwned-passwords-final-report.ipynb)

## Statistical Learning Concepts
### coding logistic regression from scratch
`python` `logistic regression` `statistical learning` `gradient descent`  
This project puts the concept of logistic regression into code. Here, logistic regression with L2 regularization is coded from scratch and packaged into an importable module called `winlogistic`. The gradient descent process used here is fast gradient descent with backtracking on the step size.  
[github repository](https://github.com/winnawat/winlogistic)  
[notebook](https://github.com/winnawat/winlogistic/blob/master/polish-code-assignment.ipynb)
