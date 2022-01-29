# ACM Research Coding Challenge (Spring 2022)

For this challange I have used 2 Jupyter notebooks for better explainability
1. [Exploratory data analysis (EDA)](https://github.com/nimblefox/ACM-Research-Coding-Challenge-S22/blob/main/Exploratory%20data%20analysis.ipynb)
2. [Preprocessing, Modelling, and Metrics (PMM)](https://github.com/nimblefox/ACM-Research-Coding-Challenge-S22/blob/main/Preprocessing%2C%20Modelling%20and%20Metrics.ipynb)


In Notebook 1 - EDA, I have done the following 
  1. Checking Summary Statistics
  2. Plotting frequency histogram
  3. Plotting a Correlation heatmap
  4. Getting inferences from the above steps to decide preprocessing plan

In Notebook 2 - PMM, I have done the following 
  1. Dropping non relevant features
  2. Encoding Nominal data
  3. Fitting the data to a Logistic regression model and performing Cross Validation
  4. Looking at Metrics of the LR model
  5. Reasoning to move on to a new model
  6. Fitting the data to a Decision Tree model and performing Cross Validation
  7. Looking at Metrics of the DT model and why I decided to stop
  8. Checking the feature importance from DT model


I had a great time working on this challange and have learnt new techniques and concepts. While, I did a lot of experimentation it has been ommited for brevity


Below is the list of References that I have used
1. https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html
2. https://machinelearningmastery.com/data-leakage-machine-learning/
3. https://stackoverflow.com/questions/28218698/how-to-iterate-over-columns-of-pandas-dataframe-to-run-regression
4. https://stackoverflow.com/questions/62972488/plotting-with-subplots-in-a-loop
5. https://towardsdatascience.com/the-search-for-categorical-correlation-a1cf7f1888c9
6. https://towardsdatascience.com/choosing-the-right-encoding-method-label-vs-onehot-encoder-a4434493149b
7. https://stackoverflow.com/questions/39409866/correlation-heatmap
8. https://towardsdatascience.com/pca-clearly-explained-how-when-why-to-use-it-and-feature-importance-a-guide-in-python-7c274582c37e
9. https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html
10. https://stackoverflow.com/questions/46598301/how-to-compute-precision-recall-and-f1-score-of-an-imbalanced-dataset-for-k-fold
11. https://developpaper.com/using-class-weight-to-improve-class-imbalance/
12. https://machinelearningmastery.com/calculate-feature-importance-with-python/
